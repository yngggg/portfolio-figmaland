<template>
    <div class="container">
        <div id="partners__wrapper">
            <ul id="contents__title">
                <li id="contents__main-txt">
                    Partners
                </li>
                <li id="contents__sup-txt">
                    We focus on ergonomics and meeting you where you work. 
                    It's only a keystroke away.
                </li>
            </ul>
            <div id="partners__items">
                <img src="../assets/partners1.png" class="partners__item-1">
                <img src="../assets/partners2.png" class="partners__item-2">
                <img src="../assets/partners3.png" class="partners__item-3">
                <img src="../assets/partners4.png" class="partners__item-4">
                <img src="../assets/partners5.png" class="partners__item-5">
                <img src="../assets/partners6.png" class="partners__item-6">
            </div>
            <a href="#" id="partners__btn">All Partners</a>
        </div>
    </div>
</template>
<style>

#partners__wrapper
{
    margin: 50px 0px;
    display: flex;
    flex-direction: column;
    gap: 50px;
}

#partners__items
{
    display: flex;
    flex-direction: row;
    gap: 60px;
    align-items: center;
    max-width: 832px;
    margin: 0 auto;
}
[class^='partners__item-']
{
    width: 60px;
    height: 60px;
}

.partners__item-3
{ height: 70px; }
.partners__item-4
{ width: 72px; }
.partners__item-5
{ height: 65px; }
.partners__item-6
{ width: 149px; }

#partners__btn
{
    width: 88px;
    max-height: 52px;
    border: 1px solid #FFFFFF;
    align-items: center;
    padding: 15px 43px;
    font-size: 17px;
    margin: 0 auto;
}
#partners__btn:hover
{ background-color: #4452FE; border: 1px solid #4452FE; }


</style>