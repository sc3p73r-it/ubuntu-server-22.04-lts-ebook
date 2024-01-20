# Ubuntu Server 22.04 LTS Administration Ebook

Linux System Administration Guide for Sysadmin

![Alt text](ubuntu.png)

About This Book
---------------
ဒီစာအုပ်လေးကိုတော့ Ubuntu Server Administration လို့အမည်ပေးထားပြီးတော့ Linux System Administration နဲ့ပတ်သက်ပြီး မလေ့လာဖူးသေးတဲ့ Beginner တွေအတွက်ရည်ရွယ်ပြီးတော့ ရေးထား ခြင်းဖြစ်ပါတယ်။
ဒီ Ubuntu Server Administration ကို Beginner Level ကနေစပြီး Advanced Level ထိရောက် အောင် Step by Step ရေးပေးသွားမှာဖြစ်ပြီးတော့ အခုမှ စလေ့လာမယ့် Beginner တွေအတွက် လွယ်ကူ ပြီး လက်တွေ့အသုံးချနိုင်အောင် ဆွေးနွေးပေးထားပါတယ်။ ဒီစာအုပ်ထဲတွင် ထည့်သွင်းထားသော Lab များကို  Ubuntu Server 22.04 LTS Version ပေါ်တွင် အခြေခံ၍အသုံးပြုမည်ဖြစ်ပါသည်။ 
ဒါကြောင့် ဒီစာအုပ်လေးဟာ Ubuntu Linux ကို စတင်လေ့လာသူတွေအနေနဲ့ လွယ်လွယ်ကူကူ လေ့လာလို့ရပြီး မိမိတို့ရောက်ချင်တယ့် ပန်းတိုင်ကိုရောက်ရှိအောင် တစ်ထောင့်တစ်နေရာကနေပဲဖြစ် ဖြစ် ပံ့ကိုးကူညီပေးချင်သည့် ရယ်ရွက်ချက်ဖြင့် ရေးသားထားခြင်းဖြစ်ပါတယ်။  ဒီစာအုပ်လေးကိုဖတ်ပြီး တော့ Linux System Administration ကိုအတော်အတန်သိသင့်သလောက်သိသွားစေမည်ဖြစ်ပါသည်။ 

Getting Stared with Ubuntu Linux
--------------------------------
ဒီအခန်းမှာတော့ Ubuntu Linux နဲ့ပတ်သက်တဲ့အကြောင်းအရာများကိုအရင်ဆုံးပြောပြပေး သွားမှာဖြစ်ပါတယ်။ Ubuntu Os သည် အခမဲ့အသုံးပြုလို့ရသည်ဖြစ်ပြီး Community နဲ့ Professional Support အားကောင်းတဲ့ Ubuntu Community လဲရှိပါတယ်။ Ubuntu ကို 20 October 2004 တွင် Canonical ဆိုတဲ့ Company က စတင်မိတ်ဆက်ခဲ့ပါတယ်။ Canonical ကိုတော့ Mark Shuttleworth ဆိုတဲ့သူက တည်ထောင်ခဲ့ခြင်းဖြစ်ပါတယ်။ “Ubuntu” သည်ရှေးခေတ် African word ကဆင်းသက်လာ ခြင်းဖြစ်ပြီးတော့ English လို “Humanity to others” လို့လည်းခေါ်ဝေါ်ထားပါတယ်။ 
 Ubuntu ကတော့ Debian base ကို အခြေခံထားတာဖြစ်ပြီးတေ့ာ 2004 ခုနှစ်နောက်ပိုင်းမှာ Ubuntu CD/DVD တွေကို အခမဲ့ဖြန့်ဝေခြင်းတွေပြုလုပ်ခဲ့ပြီး လူတွေဟာ စတင် သတိထားမိကြလာတာပဲ ဖြစ်ပါတယ်။ ဒါ့အပြင် Ubuntu ကအသုံးပြုရတာလဲလွယ်ကူသည့် အတွက် စတင်အသုံးပြုသည့် Beginner အတော်အများဟာကြိုက်ကြပါတယ်။ Ubuntu သည် နိုင်ငံတကာတွင် Ubuntu Local User Group ဆိုတာလေးတွေရှိပြီးတော့ အဲ့ထဲမှာမှ မြန်မာနိုင်ငံလဲ အပါအဝင်ဖြစ်ပါတယ်။ Ubuntu တွင် Ubuntu Desktop, Ubuntu Server, Ubuntu for IoT, Ubuntu Cloud ဆိုပြီးတော့ရှိပါတယ်။ လက်ရှိဤ စာအုပ်ကို ရေးသားနေချိန်တွင် Ubuntu Os သည် 23.10 Version ထိထွက်ပြီးနေပြီဖြစ်ပါသည်။ Ubuntu Os Version Update တွေထုတ်ပေးသည့်အခါတွင် Short Term နဲ့ Long Term ဆိုပြီး ၂မျိုးရှိပါတယ်။ လက်ရှိ ထွက်ခဲ့တယ့် Ubuntu 23.10 Version သည် Short Term Version ဖြစ်ပြီးတော့ လက်ရှိစာအုပ်ထဲ တွင် အသုံးပြုသွားမှာကတော့ Ubuntu 22.04 LTS ဖြစ်တယ့် Long Term Version Support ကို အသုံးပြု သွားမှာပဲဖြစ်ပါတယ်။ Ubuntu ရဲ့ Version နံပါတ်တွေကို သတ်မှတ်သောအခါတွင် YY.MM ဆိုပြီးသတ် မှတ်ပါတယ်။ (ဥပမာ – Ubuntu 23.10 Version ဆိုရင် 2023 ခုနှစ် 10 လပိုင်းမှာထွက်တဲ့အတွက် Ubuntu 23.10 ဆိုပြီးအသုံးပြုထားခြင်းဖြစ်ပါသည်။ ) အနောက်က Mantic Minotaur ဆိုတာကတော့ Ubuntu က သတ်မှတ်ထားတယ့် codename ပဲဖြစ်ပါတယ်။
