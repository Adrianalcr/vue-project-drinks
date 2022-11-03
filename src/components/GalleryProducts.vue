
<template class="products">

    <div class="container text-center">
        <h1>Product card</h1>
        <span>
            <a href="#" class="wsk-btn">
                <i class="fa-thin fa-cart-shopping"></i>2
            </a>
        </span>
    </div>

    <div class="shell">
        <div class="container">
            <div class="row">

                <div class="col-md-3">
                    <div class="wsk-cp-product">
                        <div class="wsk-cp-img">
                            <img src="@/assets/img/gallery/cofee.png" alt="Product" class="img-responsive" />
                        </div>
                        <div class="wsk-cp-text">
                            <h1>Cofee</h1>
                            <div class="card-footer">
                                <div class="wcf-left">
                                    <span class="price">$ 0.99</span>
                                </div>
                                <div class="wcf-right">
                                    <a href="#" class="buy-btn">
                                        <i class="fa-thin fa-cart-shopping"></i>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-md-3">
                    <div class="wsk-cp-product">
                        <div class="wsk-cp-img">
                            <img src="@/assets/img/gallery/juice.png" alt="Product" class="img-responsive" />
                        </div>
                        <div class="wsk-cp-text">
                            <h1>Fruit Juice</h1>
                            <div class="card-footer">
                                <div class="wcf-left">
                                    <span class="price">$ 3.00</span>
                                </div>
                                <div class="wcf-right">
                                    <a href="#" class="buy-btn">
                                        <i class="fa-thin fa-cart-shopping"></i>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-md-3">
                    <div class="wsk-cp-product">
                        <div class="wsk-cp-img">
                            <img src="@/assets/img/gallery/wine.png" alt="Product" class="img-responsive" />
                        </div>
                        <div class="wsk-cp-text">
                            <h1>Wine</h1>
                            <div class="card-footer">
                                <div class="wcf-left">
                                    <span class="price">$ 5.00</span>
                                </div>
                                <div class="wcf-right">
                                    <a href="#" class="buy-btn">
                                        <i class="fa-thin fa-cart-shopping"></i>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-md-3">
                    <div class="wsk-cp-product">
                        <div class="wsk-cp-img">
                            <img src="@/assets/img/gallery/beers.png" alt="Product" class="img-responsive" />
                        </div>
                        <div class="wsk-cp-text">
                            <h1>Beers</h1>
                            <div class="card-footer">
                                <div class="wcf-left">
                                    <span class="price">$ 4.00</span>
                                </div>
                                <div class="wcf-right">
                                    <a href="#" class="buy-btn">
                                        <i class="fa-thin fa-cart-shopping"></i>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>

        </div>
    </div>

</template>

<style scoped>
.shell {
    width: 100%;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;

    padding: 20px 0;
}
.row{
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    align-content: space-between;
}
.container {
    width: 100%;
    display: flex;
    flex-direction: row;
}

.wsk-cp-product {
    background: #fff;
    padding: 15px 15px;
    border-radius: 6px;
    box-shadow: 0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);
    position: relative;
    margin: 20px 20px;
    height: 350px;
    width: 250px;
}

.wsk-cp-img {
    position: relative;
    top: 15px;
    left: 50%;
    transform: translate(-50%);
    -webkit-transform: translate(-50%);
    -ms-transform: translate(-50%);
    -moz-transform: translate(-50%);
    -o-transform: translate(-50%);
    -khtml-transform: translate(-50%);
    width: 100%;
    padding: 15px;
    transition: all 0.2s ease-in-out;
}

.wsk-cp-img img {
    width: 100%;
    height: 30vh;
    transition: all 0.2s ease-in-out;
    border-radius: 50%;
}

.wsk-cp-product:hover .wsk-cp-img {
    top: -30px;
}

.wsk-cp-product:hover .wsk-cp-img img {
    box-shadow: 0 19px 38px rgba(0, 0, 0, 0.30), 0 15px 12px rgba(0, 0, 0, 0.22);
}

.wsk-cp-text h1{
    text-align: center;
    color: #ff9f0f;
}

.card-footer {
    padding: 15px 0 5px;
    border-top: 1px solid #ddd;
}

.card-footer:after,
.card-footer:before {
    content: '';
    display: table;
}

.card-footer:after {
    clear: both;
}

.card-footer .wcf-left {
    float: left;

}

.card-footer .wcf-right {
    float: right;
}

.price {
    font-size: 18px;
    font-weight: bold;
    color: #F44336;
}

a.buy-btn {
    display: block;
    color: #212121;
    text-align: center;
    font-size: 18px;
    width: 35px;
    height: 35px;
    line-height: 35px;
    border-radius: 50%;
    border: 1px solid #212121;
    transition: all 0.2s ease-in-out;
}

a.buy-btn:hover,
a.buy-btn:active,
a.buy-btn:focus {
    border-color: #FF9800;
    background: #FF9800;
    color: #fff;
    text-decoration: none;
}

.wsk-btn {
    display: inline-block;
    color: #212121;
    text-align: center;
    font-size: 18px;
    transition: all 0.2s ease-in-out;
    border-color: #FF9800;
    background: #FF9800;
    padding: 12px 30px;
    border-radius: 27px;
    margin: 0 5px;
}

.wsk-btn:hover,
.wsk-btn:focus,
.wsk-btn:active {
    text-decoration: none;
    color: #fff;
}

.red {
    color: #F44336;
    font-size: 22px;
    display: inline-block;
    margin: 0 5px;
}

@media screen and (max-width: 991px) {
    .wsk-cp-product {
        margin: 30px auto;
    }

    .wsk-cp-product .wsk-cp-img {
        top: -30px;
    }

    .wsk-cp-product .wsk-cp-img img {
        box-shadow: 0 19px 38px rgba(0, 0, 0, 0.30), 0 15px 12px rgba(0, 0, 0, 0.22);
    }


    a.buy-btn {
        border-color: #FF9800;
        background: #FF9800;
        color: #fff;
    }
}

@media (min-width: 1024px) {
    .products {
        width: 100%;
        min-height: 100vh;
        display: flex;
        align-items: center;
    }
}
</style>