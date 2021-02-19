<div dir="rtl">

# اسامی با معنی

اسامی همه جای برنامه وجود دارند . متد ها ، کلاس ها ، فضاهای نام ، آرگومان ها ، متغیر ها و ... همه و همه نام گذاری می شوند.اسامی با معنینقش مهمی در خوانایی برنامه ها و توسعه و نگه داری کد های منبع موجود دارند.اسامی باید با معنی و بیانگر ویژگی ها و کاربرد شی مورد نظر باشند ، به گونه ای که با دیدن نام شی مورد نظر عملکرد آن کامل مشخص باشد و نیاز به بررسی پیاده سازی آن نباشد.این امر موجب می شود توسعه و نگه داری سورس کد آسان و زمان توسعه آن را کاهش دهد زیرا طبق تحقیقات انجام شده در توسعه نرم افزار 70 درصد زمان صرف بررسی کد های قبلی و بررسی عملکرد اشیا می شود بنابرین صرف زمان در زدن کد خوب به خصوص نام گذاری مناسب موجب جلوگیری از صرف زمان بیشتر هنگام توسعه در جهت بررسی کد های قبلی و عملکرد اشیا می شود.
در بین برنامه نویسان حرفه ای نوتیشن ها و سبک های نوشتاری رایجی در ایجاد زبانی مشترک وجود دارد که از جمله آن می توان به :



  camelCase : در این سبک نوشتاری حروف اول کلمات کوچک و حروف دیگر بزرگ می باشد. برای مثال :
</div>
 ```java 
  int elapsedTimeInDays=1; //camelCase 
 ```
 PascalCase  : در این سبک نوشتاری حروف اول کلمات بزرگ می باشد. برای مثال : <br/>   <code> Complex FulcrumPoint = Complex.FromRealNumber(23.0); //PascalCase </code> </li>
  <li> <strong> kebab-case </strong> : در این سبک نوشتاری حروف اول کلمات کوچک و بین کلمات  - قرار می گیرد. برای مثال : <br/>   <code> int elapsed-time-in-days=1; //kebab-case </code> </li>
  <li> <strong> snake_case </strong> : در این سبک نوشتاری حروف اول کلمات کوچک و بین کلمات _ قرار می گیرد. برای مثال : <br/>   <code> int elapsed_time_in_days=1; //snake_case </code> </li>
  <li> <strong> Hungarian </strong> : در این سبک نوشتاری نوع داده ای در ابتدا و کلمات بعدی با حروف بزرگ شروع می شوند. برای مثال : <br/>   <code> string strName="Mohammad"; //Hungarian </code></li>
</ul>
  <div>
    <p dir="rtl"> - <b> در کد تمیز نام توابع و کلاس ها و اینترفیس ها و فضای نام ها به سبک PascalCase نوشته می شوند و متغیر ها و آرگومان ها به سبک camelCase می باشند. </b> </p>
    <p dir="rtl"> تا اینجا از اهمیت انتخاب اسامی مناسب برای اشیا مطلع شدیم اما این اسامی باید چه ویژگی هایی داشته باشند در زیر این ویژگی ها را همراه با چند مثال بررسی می کنیم: </p>
    <ul dir="rtl">
       <li> <strong> استفاده از اسم های بیان کننده منظور </strong> : نام شی باید گویای عملکرد شی باشد به گونه ای که با دیدن نام شی  لازم به بازبینی کد شی نباشد.
      </br>
    <p dir="rtl"> برای مثال کد زیر گویای عملکرد تابع نیست. </p>
  
```java
 public List getThem() {
        List list1 = new ArrayList;
                for (int[] x : theList)
                        If (x[0] == 4)
                                List1.add(x);
         Return list1;
}
```
 </div>
     <p dir="rtl"> برای مثال کد زیر گویای عملکرد است. </p>
     <div >   
     <pre ><span class="pl-k">public</span> <span class="pl-smi">List</span> getFlaggedCells() {
        <span class="pl-smi">List</span> flaggedCells <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-smi">ArrayList</span>();
        <span class="pl-k">for</span> (<span class="pl-k">int</span>[] cell <span class="pl-k">:</span> gameBoard)
                <span class="pl-smi">If</span> (cell[<span class="pl-c1">STATUS_VALUE</span>] <span class="pl-k">==</span> <span class="pl-c1">FLAGGED</span>)
                        flaggedCells<span class="pl-k">.</span>add(cell);
        <span class="pl-k">return</span> flaggedCells;
}</pre>
    </div>
      </li>
       <li dir="rtl"> <strong> خودداری از دادن اطلاعات اشتباه </strong> : نام ها نباید بی معنی و مختصر باشند و یا از نام گذاری های مشابه دوری کنید. </li>
    </ul>
   </div>

</div>
