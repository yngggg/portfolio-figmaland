<template>
    <div class="container">
        <div id="header__wrapper">
            <img src="../assets/headerLogo.png" id="header__logo">
            <ul id="header__links">
                <a href="#" id="header__link">Home</a>
                <a href="#" id="header__link">Product</a>
                <a href="#" id="header__link">About</a>
                <a href="#" id="header__link">Contact</a>
            </ul>
            <button type="button" id="header__login">
                Login
            </button>
            <button id="show__header-links">
                <svg width="66" height="53" viewBox="0 0 66 53" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M11 13.25H55V17.6667H11V13.25ZM22 24.2917H55V28.7083H22V24.2917ZM35.75 35.3333H55V39.75H35.75V35.3333Z" fill="white"/>
                </svg>
            </button>
        </div>
    </div>
</template>
<style>

#header__wrapper
{
    height: 119px;
    padding: 30.5px 0px;
    display: flex;
    justify-content: space-between;
}
#header__logo
{
    height: 58px;
    width: 186px;
}
#header__links
{
    padding: 20px 0px;
    width: 393px;
    display: flex;
    justify-content: space-between;
    font-size: 16px;
}
#header__login
{
    width: 139px;
    max-height: 52px;
    border: 1px solid #FFFFFF;
    align-items: center;
    padding: 15px 36px;
    padding-bottom: 22px;
    font-size: 17px;
}
#show__header-links
{
    max-height: 53px;
}

</style>