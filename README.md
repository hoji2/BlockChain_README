<h1 align="center">Welcome to blockchain-sub3 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.2.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/hoji2/BlockChain_README" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/hoji2/BlockChain_README" target="_blank">
    <img alt="License: non_HAEJAE" src="https://img.shields.io/badge/License-5-yellow.svg" />
  </a>
</p>

> 블록체인 기반 P2P 경매시스템

### ✨ [Demo](https://github.com/hoji2/BlockChain_README)

# Bloction

블록체인 기반 P2P 경매 시스템

## 1) 지갑생성

이더리움 기반 스마트컨트랙트 거래에 필요한 지갑을 생성한다. 위 사이트의 사용자들은 지갑 생성 시 발급되는  **Private Key**를 숙지하여한다.  다양한 기능을 이용할 시 개인 인증에 **Private Key**를 사용하기 때문이다.

## 2) 작품등록 및 상세보기

작품을 등록할 사용자는 작품의 이름, 작품설명, 공개 여부등을 설정하여 요청하면 관련 작품 내역은 데이터베이스에 등록되며, 경매가 진행되는 동안 해당 작품의 **소유내역**을 상세보기를 통해 확인할 수 있다.

## 3)경매등록

작품의 소유자는  경매등록 시 최저가, 시작 및 종료일자등을 입력하여 경매를 생성할 수 있다. 경매를 블록체인 원장에 등록하는 과정에서 **수수료**가 발생한다.

## 4)입찰 

입찰자는 이더리움을 충전하고 경매에 올라온 작품을 입찰할 수 있다. 최초 입찰 이후로 해당 작품에서 **최고 입찰자**와 **최고 입찰금액**을 가시적으로 확인할 수 있다.

## 5)낙찰 및 경매종료

경매를 생성한 사용자는 경매 마감시간 내 경매종료가 가능하며, 경매종료시 낙찰금을 회수한다. 최고입찰자 이외에 입찰자들은 **경매가 종료되는 시점**에서 자신의 입찰금을 회수받는다. 


## Install

```sh
npm install
```

## Usage

```sh
npm run serve
```

## Run tests

```sh
npm run  test
```

## Author
👤 **Hojin**

* Website: Hojin
* Github: [@hoji2](https://github.com/hoji2)


## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/hoji2/BlockChain_README).

## Show your support

Give a ⭐️ if this project helped you!

<a href="https://www.patreon.com/4">
  <img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>

## 📝 License

This project is [5](https://github.com/hoji2/BlockChain_README) licensed.

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
