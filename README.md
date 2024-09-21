# Geth

https://geth.ethereum.org/downloads - geth 다운로드
https://geth.ethereum.org/docs/fundamentals/private-network - Documentation

### 명령어 모음

만약 전역에 있는 geth를 사용하고 싶다면
```bash
geth --datadir ./data init ./genesis.json
geth --datadir ./data --http --http.api "admin, web3, eth, personal" console
geth attach http://127.0.0.1:8545
```


체인스토리지 초기화 명령어
```bash
./geth --datadir ./data init ./genesis.json
```

Geth 실행
```bash
./geth --datadir ./data --http --http.api "admin, web3, eth, personal" console
```

attach 명령어로 커맨드를 입력할 수 있는 콘솔 생성
```bash
./geth attach http://127.0.0.1:8545
```