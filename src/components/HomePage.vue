<template>
    <div class="con">
        <div class="hero">
        <div class="hero__con">
            <div class="hero__sub">سلام! من هانیه حائری هستم</div>
        <div class="hero__title">دندانپزشک</div>
        <div class="hero__text">جراح - دندانپزشک، فارغ التحصیل دکترای دندانپزشکی از دانشگاه آزاد اسلامی تهران با ۶ سال سابقه کار</div>
        <div class="hero__btn">
            <v-btn
                elevation="2"
                rounded
                dark
                color="#5D3366"
            >تماس با من<v-icon
        right
        dark
      >
        mdi-phone
      </v-icon></v-btn>
        </div>
        </div>
    </div>
    <div   class="subhero">
        <div   class="subhero__title" >درباره من</div>
        <div  class="subhero__text">لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد. کتابهای زیادی در شصت و سه درصد گذشته، حال و آینده شناخت فراوان جامعه و متخصصان را می طلبد تا با نرم افزارها شناخت بیشتری را برای طراحان رایانه ای علی الخصوص طراحان خلاقی و فرهنگ پیشرو در زبان فارسی ایجاد کرد. در این صورت می توان امید داشت که تمام و دشواری موجود در ارائه راهکارها و شرایط سخت تایپ به پایان رسد وزمان مورد نیاز شامل حروفچینی دستاوردهای اصلی و جوابگوی سوالات پیوسته اهل دنیای موجود طراحی اساسا مورد استفاده قرار گیرد.

        </div>
        <div  class="subhero__btn"></div>
    </div>

    </div>

</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>

.con{
    display: flex;
    justify-content: center;
}

.hero{
    width: 1134px;

    &__con{
        width: 370px;
    }
    

    &__sub{
        font-size: 24px;
        font-weight: bold; 
        color: #1F1F1F;  
    }

    &__title{
        font-size: 64px;
        font-weight: bold;
        color: #5D3366;
    }

    &__text{
        font-size: 16px;
        color: #1F1F1F;
    }
}

</style>