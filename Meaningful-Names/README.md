<h1 dir="rtl">اسامی با معنی</h1>
<div dir="rtl">
  <p dir="rtl"> اسامی با معنی نقش مهمی در خوانایی برنامه ها و توسعه و نگه داری کد های منبع موجود دارند.اسامی باید با معنی و بیانگر ویژگی ها و کاربرد شی مورد نظر باشند.   </p>
<p dir="rtl"> در بین برنامه نویسان حرفه ای نوتیشن ها و سبک های نوشتاری رایجی در ایجاد زبانی مشترک وجود دارد که از جمله آن می توان به : <p>
<ul dir="rtl">
  <li> <strong> camelCase </strong> : در این سبک نوشتاری حروف اول کلمات کوچک و حروف دیگر بزرگ می باشد. برای مثال :  <br/>  <code> int elapsedTimeInDays=1; //camelCase </code> </li>
  <li> <strong> PascalCase </strong> : در این سبک نوشتاری حروف اول کلمات بزرگ می باشد. برای مثال : <br/>   <code> Complex FulcrumPoint = Complex.FromRealNumber(23.0); //PascalCase </code> </li>
  <li> <strong> kebab-case </strong> : در این سبک نوشتاری حروف اول کلمات کوجک و بین کلمات  - قرار می گیرد. برای مثال : <br/>   <code> int elapsed-time-in-days=1; //kebab-case </code> </li>
  <li> <strong> snake_case </strong> : در این سبک نوشتاری حروف اول کلمات کوجک و بین کلمات _ قرار می گیرد. برای مثال : <br/>   <code> int elapsed_time_in_days=1; //snake_case </code> </li>
  <li> <strong> Hungarian </strong> : در این سبک نوشتاری نوع داده ای در ابتدا و کلمات بعدی با حروف بزرگشروع می شوند. برای مثال : <br/>   <code> string strName="Mohammad"; //Hungarian </code></li>
</ul>
  <div dir="rtl">
    <p dir="rtl">  در کد تمیز نام توابع و کلاس ها و اینترفیس ها و فضای نام ها به سبک PascalCase نوشته می شود و متغیر ها و آرگومان ها به سبک camelCase می باشند. </p>
    <ul dir="rtl">
       <li> <strong> استفاده از اسم‌های بیان کننده منظور </strong> : نام شی باید گویای عملکرد شی باشد به گونه ای که با دیدن نام شی  لازم به بازبینی شی نباشد .
      </br>
    <p dir="rtl"> برای مثال کد زیر گویای عملکرد تابع نیست. </p>
    <div dir="ltr">   
   <pre dir="ltr"> <span class="pl-k">public</span> <span class="pl-smi">List</span> getThem() {
        <span class="pl-smi">List</span> list1 <span class="pl-k">=</span> <span class="pl-k">new</span> ArrayList;
                <span class="pl-k">for</span> (<span class="pl-k">int</span>[] x <span class="pl-k">:</span> theList)
                        <span class="pl-smi">If</span> (x[<span class="pl-c1">0</span>] <span class="pl-k">==</span> <span class="pl-c1">4</span>)
                                <span class="pl-smi">List1</span><span class="pl-k">.</span>add(x);
         <span class="pl-smi">Return</span> list1;
}</pre>
 </div>
        <p dir="rtl"> برای مثال کد زیر گویای عملکرد است. </p>
     <div dir="ltr">   
    <pre dir="ltr"><span class="pl-k">public</span> <span class="pl-smi">List</span> getFlaggedCells() {
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
