<template>
        <div id="preview__wrapper">
            <ul id="preview__text">
                <li id="preview__title">
                    Work at the speed of thought
                </li>
                <li id="preview__suptitle">
                    Most calendars are designed for teams. Slate is designed for freelancers who want a simple way to plan their schedule.
                </li>    
            </ul>
            <ul id="preview__buttons">
                <button id="preview__try">Try For Free</button>
                <button id="preview__learn">Learn More</button>
            </ul>
        </div>
        <div id="dashboards__wrapper">
            <img src="../assets/dashboard.png" alt="" id="dashboard__img">
            <div id="dashboards__layer"></div>
        </div>
</template>
<style>
#preview__wrapper
{
    margin-top: 35px;
    display: flex;
    flex-direction: column;
    gap: 85px;
}
#preview__text
{
    display: flex;
    flex-direction: column;
    gap: 17px;
    text-align: center;
    max-width: 729px;
    margin: 0 auto;
    font-size: 80px;
    font-weight: 500;
    line-height: 88px;
    letter-spacing: 0.2px;

}
#preview__suptitle
{
    max-width: 602px;
    margin: 0 auto;
    font-size: 20px;
    font-weight: 400;
    line-height: 30px;
}

#preview__buttons
{
    max-width: 387px;
    margin: 0 auto;
    display: flex;
    flex-direction: row;
    gap: 35px;
}
#preview__try,#preview__learn
{
    background-color: #4452FE;
    width: 178px;
    height: 65px;
}
#preview__learn
{
    background-color: transparent;
    border: 1px solid #fff;
}
#preview__learn:hover,#header__login:hover
{
    background-color: #4452FE;
    border: 1px solid #4452FE;
}
#preview__try:hover
{
    background-color: transparent;
    border: 1px solid #fff;
}

#dashboards__wrapper
{
    height:60%;
}
#dashboard__img
{
    width: 81.5%;
    display: block;
    margin-top:40px;
    margin: 0 auto;
    margin-top: 40px;
    padding-right: 6px;
}

#dashboards__layer
{
    width: 100%;
    height: 57.4%;
    position: absolute;
    left: 0%;
    right: 0%;
    margin-bottom: -28%;
    bottom: 0%;
    background: linear-gradient(180deg, rgba(0, 0, 0, 0) 0%, #0E0E0E 66.15%);
}

</style>