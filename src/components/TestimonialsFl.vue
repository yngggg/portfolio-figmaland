<template>
    <div class="container">
        <div id="testimonials__wrapper">
            <ul id="contents__title">
                <li id="contents__main-txt">
                    Testimonials
                </li>
            </ul>
            <div id="testm__items-wrap">
                <div v-for="comment in testmList" :key="comment.id" id="testm__item">
                    <ul id="tstitem__title">
                        <img :src="comment.userIcon" id="tstitem__icon">
                        <ol id="tstitem__title-txt">
                            <li id="tstitem__main-txt">{{ comment.userName }}</li>
                            <li id="tstitem__sup-txt">{{ comment.userJob }}</li>
                        </ol>
                    </ul>
                    <li id="tstitem__text">{{ comment.userComment }}</li>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default{
    data(){
        return{
            testmList : [
                {id : 1, userIcon : require("../assets/userIcon1.png"), userName : 'Claire Bell', userJob : 'Designeer', userComment : 'Slate helps you see how many more days you need to work to reach your financial goal for the month and year. Slate helps you see how many more days you need to work to reach your financial goal for the month and year.your financial goal for the month and year.' },
                {id : 2, userIcon : require("../assets/userIcon2.png"), userName : 'Francisco Lane', userJob : 'Designeer', userComment : 'Slate helps you see how many more days you need to work to reach your financial goal for the month and year. Slate helps you see how many more days you need to work to reach your financial goal for the month and year.' },
                {id : 3, userIcon : require("../assets/userIcon3.png"), userName : 'Ralph Fisher', userJob : 'Designeer', userComment : 'Slate helps you see how many more days you need to work to reach your financial goal for the month and year. Slate helps you see how many more days you need to work to reach your financial goal for the month and year.' },
                {id : 4, userIcon : require("../assets/userIcon4.png"), userName : 'Jorge Murphy', userJob : 'Designeer', userComment : 'Slate helps you see how many more days you need to work to reach your financial goal for the month and year. Slate helps you see how many more days you need to work to reach your financial goal for the month and year.' },
            ]
        }
    }
}


</script>
<style>

#testimonials__wrapper
{
    display: flex;
    flex-direction: column;
    gap: 50px;
    margin:200px 0 100px ;
}

#testm__items-wrap
{
    max-width: 883px;
    margin: 0 auto;
    display: grid;
    grid-template-rows: 1fr ;
    grid-template-columns: 1fr 1fr ;
    gap: 22px;
}

#testm__item
{
    padding: 40px;
    padding-right: 70px;
    max-width: 318px;
    display: flex;
    flex-direction: column;
    gap: 30px;
    border: 1px solid #DEDEDE;
    border-radius: 10px;
}
#tstitem__title-txt
{
    margin-top: 7.5%;
    font-weight: 500;
    font-size: 16px;
    line-height: 24px;
    letter-spacing: 0.2px;
    display: flex;
    flex-direction: column;
    gap: 2px;
}
#tstitem__title
{ 
    display: flex; 
    flex-direction: row; 
    gap: 25px;
}
#tstitem__text
{
    font-weight: 400;
    font-size: 16px;
    line-height: 24px;
    letter-spacing: 0.2px;
}

</style>