<template>
    <div id="opent__main-wrap">
        <div id="opent__wrap">
            <ul id="opent__textzone">
                <li id="opent__title">
                    OpenType feature and Variable fonts
                </li>
                <button id="opent__btn">Try For Free</button>
            </ul>
            <img src="../assets/opent1.png" id="opent__img">
        </div>
    </div>
</template>
<style>


#opent__main-wrap
{
    margin: 180px 0;
}
#opent__wrap
{
    max-width: 1219px;
    margin: 0 auto;
    display: flex;
    flex-direction: row;
    gap: 100px;
    box-shadow: 0px 4px 31px rgba(0, 0, 0, 0.15);
    border-radius: 33px;
    background: #343434;
}
#opent__textzone
{
    display: flex;
    flex-direction: column;
    gap: 37px;
    font-weight: 300;
    font-size: 52px;
    line-height: 62px;
    letter-spacing: 0.2px;
    max-width: 450px;
    padding: 65px 0px;
    margin-left: 94px;
}
#opent__title
{
    max-width: 499px;
}
#opent__btn
{
    background-color: #4452FE;
    width: 232px;
    height: 52px;
    align-items: center;
}
#opent__btn:hover{ border: 1px solid #4452FE; background-color: transparent; }

#opent__img
{
    width: 585px;
    height: 350px;
}

</style>