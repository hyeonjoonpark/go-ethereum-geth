# Geth

https://geth.ethereum.org/downloads - geth 다운로드

### 명령어 모음


체인스토리지 초기화 명령어
```bash
./geth --datadir ./data init ./genesis.json
```

Geth 실행
```bash
./geth --datadir ./data --http --http.api "admin, web3, eth, personal" console
```