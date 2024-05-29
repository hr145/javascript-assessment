# javascript-assessment
const NFTs = []

function mintNFT (_name, _eyeColor, _shirtType, _bling) {
    const NFT = {
        "name": _name,
        "eyeColor": _eyeColor,
        "shirtType": _shirtType,
        "bling": _bling
        
    }
    NFTs.push(NFT);
    console.log("Minted: " + _name);
    
}
function listNFTs () {
    for(let i = 0; i < NFTs.length; i++) {
        console.log(NFTs[i]);
    }
    
}
function getTotalSupply(){
    console.log(NFTs.length);
}
mintNFT("Harsh", "Red", "Hoodie", "Silver Chain");
listNFTs();
getTotalSupply();

