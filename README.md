![NFTSITE](https://github.com/BCS-4/react_project_KIM_KYEONG-SEOG/assets/148549192/49dff1d9-3ba5-4e45-9a03-8b289cc213a9)


<h1>
    NFT SHOP
</h1>

<h3>
    사이트 소개
</h3>
<p>- 내가 만든 NFT를 전시, 판매등록, 판매, 다른 사용자의 구매기능을 제공하는 사이트입니다.</p>


<h3>
    특징 및 기능
</h3>
<p>- 특징 : NFT의 컨셉인 파워퍼프걸이 두드러지도록 웹페이지의 구성을 흑백의 색상, 간단한 UI로 설정하였습니다 </p>
<p>- 기능 : HOME에서는 MINTING된 NFT를 볼 수 있도록 구현, 내가 가지고 있는 NFT의 판매 및 구매 가능한 NFT를 구매할 수 있도록 기능을 구현하였습니다.</p>

<pre>
<code>

NFT DASHBOARD
├── contracts # Solidity folder
    │ ├── MintNFT.sol # Smartcontract for minting NFTs
    │ └── SaleNFT.sol # Smartcontract for selling NFTs
    └── frontend # React frontend folder
    ├── public # Logo image
    └── src # Source files
    ├── abis # Abi folder
    │ └── contractAddress.tsx # Smartcontract address file
    ├── components # Components
    │ ├── Footer.tsx  
    │ ├── Header.tsx
    │ ├── Layout.tsx
    │ ├── MintModal.tsx
    │ ├── MyNftCard.tsx
    │ ├── NftCard.tsx
    │ └── SaleNftCard.tsx
    ├── pages # Pages
    │ ├── detail.tsx
    │ ├── home.tsx
    │ ├── my.tsx
    │ └── sale.tsx  
    ├── types # Typescript interface file
    └── App.tsx

</code>
</pre>
