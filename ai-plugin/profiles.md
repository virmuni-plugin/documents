## پروفایل ها (نام جدول --> profiles)

> نام اندپوینت : profiles
> > مسیر : virmuni/[plugin-name]/profiles/
> > > انواع : GET

> نام اندپوینت : profile
> > مسیر : [id]/virmuni/[plugin-name]/profile/
> > > انواع : GET, POST, PUT, DELETE


### تنظیمات پروفایل

1 . نام پروفایل (* الزامی)
> دیتابیس : profileName => String

2 . آیدی فاین تیون انتخاب شده
> دیتابیس : fineTuneID => int
> > پیش فرض : 0

### تنظمیات OpenAI

1 . کلید API
> دیتابیس : apiKey => String
> > پیش فرض : "public"
  - عمومی (public)
  - خصوصی (ورودی از کاربر)

2 . مدل
> دیتابیس : model => String
> > پیش فرض : "gpt-3.5-turbo"

3 . حداکثر توکن
> دیتابیس : maxToken => Int
> > پیش فرض : 4096

4 . لحن محتوا
> دیتابیس : tone => String
> > پیش فرض : "none"

5 . سبک محتوا
> دیتابیس : writingStyle => String
> >  پیش فرض : "none"

6 . دما
> دیتابیس : temperature => Float
> >  پیش فرض : 1.0

7 . بالاترین احتمال
> دیتابیس : topP => Float
> > پیش فرض : 1.0

8 . جریمه فرکانس
> دیتابیس : frequencyPenalty => Float
> > پیش فرض : 0

9 . جریمه حضور
> دیتابیس : presencePenalty => Float
> > پیش فرض : 0
