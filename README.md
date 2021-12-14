.product-name{
    display: grid;
    grid-template-columns: .5fr 2fr;
    width: 25vw;
    align-items: center;
    justify-self: start;
    column-gap: none;
    grid-column: 1/5;
}
.remove{
    order: 1;
}
.product-1-ram{
    order:2;
    grid-column: 2/4;
}
.product-1-price{
    order: 3;
}
.product-1-quantity{
    order: 5;
}
.product-1-image>img{
    width: 100%;
}
