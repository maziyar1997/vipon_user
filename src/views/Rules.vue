<template>
  <Navbar :text="navbarText" />
  <div class="main-section">
    <div class="rules">
      <p>
        1) مالکيت معنوي اطلاعات موجود در این سامانه متعلق به باشگاه مشتريان
        ویپون مي‌باشد.
      </p>
      <p>
        2) مطابق قوانين بين‌المللي کپي‌رايت ، کليه‌ی مندرجات اين پايگاه شامل
        لوگوها، تصاوير، مندرجات، نرم‌افزارها و... جزء دارايي‌هاي باشگاه مشتريان
        ویپون بوده و هر گونه استفاده از آن ممنوع و پیگرد قانونی دارد.
      </p>
      <p>
        3) کليه‌ی خدمات و اطلاعات اين سامانه براي استفاده‌ی اعضاي باشگاه مشتريان
        ویپون بوده و هرگونه سوءاستفاده از آن داراي پيگرد قانوني مي‌باشد.
      </p>
      <p>
        4) به منظور حفظ حريم خصوصي افراد، باشگاه مشتريان ویپون هيچ يک از اطلاعات
        ارائه شده از سوي اعضا و اطلاعات مربوط به اعتبارهای کیف پول ايشان را در
        اختيار سايرين قرار نخواهد داد.
      </p>
      <p>
        5) اطلاعات وارد شده از سوي اعضای باشگاه مشتریان صرفاً توسط باشگاه
        مشتريان ویپون و واحدهاي تابعه و به منظور ارتقاي سطح کيفي خدمات ارائه شده
        مورد بهره‌برداري قرار خواهد گرفت.
      </p>
      <p>
        6) در هنگام عضویت در باشگاه مشتريان ویپون، کاربران حق درج اطلاعات شخص
        دیگری غیر از خود را نداشته و تعهد می‌نمایند که اطلاعات خود را به صورت
        صحیح وارد نمایند. در صورت ورود اطلاعات ناقص يا نادرست، مسئولیت عواقب
        بعدی این عمل بر عهده‌ کاربر می‌باشد. همچنین اعضا باشگاه مشتریان تعهد
        می‌نمایند هرگونه تغییر در مشخصات فردی خود را در اسرع وقت در سامانه
        باشگاه مشتريان ویپون اصلاح نمایند، در غیر این‌صورت، این سامانه هیچ‌گونه
        مسؤولیتی در قبال تبعات ناشی از عدم صحت اطلاعات موجود نخواهد داشت.
      </p>
      <p>
        7) در صورت تشخيص عدم صحت اطلاعات ارائه شده از سوي افراد، باشگاه مشتريان
        ویپون مي تواند نسبت به اصلاح و جايگزيني آن با اطلاعات صحيح اقدام نمايد.
      </p>
      <p>
        8) هر کاربری که دارای حساب کاربری در سامانه باشگاه مشتريان ویپون باشد در
        قبال هر فعالیتی که بتوان در بخش کاربری انجام داد مسئول بوده و این
        مسئولیت شامل محتوا، عکس‌ها و ... می‌باشد. در صورت عدم حفظ آن، باشگاه
        مشتريان ویپون عواقب ناشی از آن را بر عهده نخواهد گرفت.
      </p>
      <p>
        9) هرگونه نقل قول از مطالب اين سامانه، صرفاً براي پايگاه‌هايی که منافع
        غيرتجاري را دنبال مي‌کنند با ذکر منبع، مجاز است.
      </p>
      <p>10) هرگونه تلاش براي دسترسي غيرمجاز به اجزا، اسناد، اطلاعات، محتويات و... اين سامانه از طريق رمزگشايي، هک و هر روش غيرمجاز ديگر ممنوع و پیگرد قانونی دارد.</p>
      <p>11)  استفاده از هر برنامه، الگوريتم يا عمليات براي کپی يا هدايت بخشي از اطلاعات اين پايگاه ممنوع مي باشد.</p>
      <p>12)  محدوده فعاليت اعضا در باشگاه ، صرفاً انجام فعالیت‌های مجاز منطبق بر اهداف باشگاه بوده و ارسال هرگونه مطالب خلاف قانون و اخلاق، ويروس‌هاي رايانه‌اي، درخواست‌هاي تجاري و تبليغاتي، فعاليت‌هاي سياسي، نامه‌هاي زنجيره‌اي و... ممنوع مي‌باشد و در صورت وارد آمدن هرگونه خسارت به باشگاه مشتريان ویپون و واحدهاي تابعه، ناشي از فعاليت اعضا خارج از حدود تعيين شده، مسؤوليت جبران آن بر عهده شخص يا اشخاص خاطي مي‌باشد.</p>
      <p>13)  هر گونه تصميم‌گيري در خصوص اعتبارها اعم از نحوه‌ی کسب، سقف قابل اکتساب، مدت زمان اعتبار، اختيارات اعضا در استفاده و شرکت در طرح‌ها و قرعه‌کشي‌ها، تعديل، ارزش ريالي امتيازات و... همچنين تصميم‌گيري درخصوص تغيير زمان‌بندي اعتبارها و طرح‌ها، توقف عضويت اعضاي غيرفعال، اعطاي جوايز و پاداش‌ها و... در اختيار کسب و کارهای طرف قرارداد باشگاه مشتريان ویپون مي باشد و هيچ يک از افراد حق ادعا يا اعتراضي در اين خصوص ندارند.</p>
      <p>14)  هرگاه براي باشگاه مشتريان ویپون محرز گردد که اعتبار کسب شده توسط هر يک از اعضا با انجام عمليات غيرواقعي و صوري کسب شده است، باشگاه اختيار دارد به صورت يکطرفه و بدون اعلام قبلي نسبت به توقف فعاليت ايشان در هر مرحله‌اي که باشند، اقدام نمايد و افراد مذکور حق هرگونه ادعا و اعتراضي را از خود سلب و ساقط مي‌نمايند.</p>
      <p>15)  در صورت بروز هرگونه مشکل فني و محدوديت در دسترسي به سامانه، باشگاه مشتريان ویپون نهايت تلاش خود را جهت رفع مشکل در اسرع وقت خواهد نمود ليکن هيچگونه تعهد و مسئوليتي در قبال مشکلات احتمالي به وجود آمده نخواهد داشت.</p>
      <p>16)  وجود لينک باشگاه مشتريان ویپون در وبسايت‌ها و وبلاگ‌ها به معناي تاييد محتواي آنها از سوي باشگاه نمي‌باشد.</p>
      <p>17)  کليه‌ی اعضاي باشگاه، ضمن ثبت‌نام در باشگاه، مقررات مربوطه را مطالعه نموده و موافقت خود را با شرايط آن اعلام مي نمايند.</p>
      <p>18)  در صورت انجام هر گونه تخلف و عدم رعايت قوانين و مقررات مندرج در این سامانه، باشگاه مشتريان ویپون حق دارد حسب صلاحديد خود نسبت به پيگيري موضوع از طريق مراجع قضايي، واحدهاي حقوقي و ساير نهادهاي مرتبط اقدام نمايد.</p>
    </div>
  </div>
  <Footer />
</template>

<script>
import Navbar from '@common/Navbar.vue'
import Footer from '@common/BaseFooter.vue'
export default {
  name : 'rules',
  data(){
    return {
      navbarText : 'قوانین'
    }
  },
  components:{
    Navbar,
    Footer
  }
};
</script>

<style scoped>
p {
  margin: 10px 0 15px;
  font-size: 15px;
  text-align: justify;
}
.rules{
  width: 94%;
  margin: 0 auto;
}
</style>