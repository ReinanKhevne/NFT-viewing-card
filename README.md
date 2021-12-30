# NFT-viewing-card
Cartão responsivo para vizualização nft

main .image-principal {
    padding: 1rem 1rem 0 1rem;
    position: relative; 
}

main .image-principal img {
    width: 100%;
    border-radius: .8rem;     
}

  /* Ajuste da imagem "olho" */

main .img-view img {
    opacity: 0;
    position: absolute;
    top: 45%;
    left: 45%;
    width: 48px;

}

main .img-view img:hover {
    opacity: 1;