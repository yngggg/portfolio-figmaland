<template>
    <div id="contents__wrapper">
        <div class="container">
            <ul id="contents__title">
                <li id="contents__main-txt">
                    Contents
                </li>
                <li id="contents__sup-txt">
                    We focus on ergonomics and meeting you where you work. 
                    It's only a keystroke away.
                </li>
            </ul>
            <div id="contents__items">
                <div id="contents__item">
                    <ul id="contents__head">
                        <li id="chead__title">Work</li>
                        <li id="chead__text">
                            Ever wondered if you're too reliant on a client for work? Slate helps you identify .
                        </li>
                    </ul>
                    <a href="#" id="contents__btn">Sigh Up</a>
                    <img src="../assets/contents1.png" id="contents__img">
                </div>
                <div id="contents__item">
                    <ul id="contents__head">
                        <li id="chead__title">Work</li>
                        <li id="chead__text">
                            Ever wondered if you're too reliant on a client for work? Slate helps you identify .
                        </li>
                    </ul>
                    <a href="#" id="contents__btn2">Try For Free</a>
                    <img src="../assets/contents2.png" id="contents__img2">
                </div>
            </div>
        </div>
    </div>
</template>
<style>

#contents__wrapper
{ margin-top: 40px; }
#contents__title
{
    max-width: 551px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 15px;
    font-weight: 400;
    font-size: 52px;
    line-height: 62px;
    letter-spacing: 0.2px;
    text-align: center;
}
#contents__sup-txt
{
    font-weight: 400;
    font-size: 20px;
    line-height: 30px;
    letter-spacing: 0.2px;
}

#contents__items
{ 
    display: flex;
    flex-direction: row;
    gap: 50px;
    max-width: 864px;
    margin: 0 auto;
    margin-top: 46px;
}
#contents__item
{
    box-shadow: 0px 4px 31px rgba(0, 0, 0, 0.15);
    border-radius: 10px;
    border: 1px solid #D3D3D3;
    background-color: #fff;
    max-width: 476px;
    padding: 40px 0px ;
    display: flex;
    flex-direction: column;
    gap: 57px;
}
#chead__title,#chead__text{ color: #000; }
#contents__head
{  
    font-weight: 600;
    font-size: 20px;
    line-height: 30px;
    letter-spacing: .1px;
    display: flex;
    flex-direction: column;
    gap: 30px;
    max-width: 288px;
    margin: 0 auto;
    text-align: center;
}
#chead__text
{
    font-weight: 400;
    font-size: 16px;
    line-height: 24px;
    letter-spacing: .2px;
    max-width: 250px;
    margin: 0 auto;
}
#contents__btn,#contents__btn2
{  
    display: block;
    align-items: center;
    padding: 18px 36px 17px;
    margin: 0 auto;
    text-align: center;
    width: 85px;
    height: 17px;
    background: #4452FE;
    box-shadow: 0px 4px 31px rgba(0, 0, 0, 0.15);
}
#contents__btn2{ margin-top: -27px; width: 118px;}
#contents__img,#contents__img2
{
    display: block;
    max-width: 405px;
    margin: 0 auto;
}
#contents__img2{ margin-top: -27px; }


</style>