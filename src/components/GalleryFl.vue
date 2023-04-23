<template>
    <div class="container">
        <div id="gallery__wrapper">
            <ul id="contents__title">
                <li id="contents__main-txt">
                    Gallery
                </li>
                <li id="contents__sup-txt">
                    We focus on ergonomics and meeting you where you work. 
                    It's only a keystroke away.
                </li>
            </ul>
            <ul class="gallery__items-line1">
                <img src="../assets/gallery1.png" id="line1__item">
                <img src="../assets/gallery2.png" id="line1__item">
                <img src="../assets/gallery3.png" id="line1__item">
                <img src="../assets/gallery4.png" id="line1__item">
            </ul>
            <ul class="gallery__items-line2">
                <img src="../assets/gallery5.png" id="line2__item">
                <img src="../assets/gallery6.png" id="line1__item">
                <img src="../assets/gallery7.png" id="line2__item">
            </ul>
            <button id="gallery__btn">See more</button>
        </div>
    </div>
</template>
<style>

#gallery__wrapper
{
    margin-top: 200px;
    margin-bottom:150px;
    display: flex;
    flex-direction: column;
    gap: 44px;
}
[class^='gallery__items-']
{ 
    display: flex; 
    flex-direction: row; 
    gap: 33px; 
}
.gallery__items-line1
{ 
    max-width: 999px; 
    margin: 0 auto; 
}
#line1__item,#line2__item,#line2__item-l
{
    border-radius: 12px;
    width: 225px;
    height: 285px;
}
.gallery__items-line2
{
    width: 100%;
}
#line2__item
{ width: 395px; }



#gallery__btn
{
    width: 159px;
    max-height: 52px;
    border: 1px solid #FFFFFF;
    align-items: center;
    padding: 15px 36px;
    padding-bottom: 22px;
    font-size: 17px;
    margin: 0 auto;
}
#gallery__btn:hover
{ background-color: #4452FE; border: 1px solid #4452FE }
</style>