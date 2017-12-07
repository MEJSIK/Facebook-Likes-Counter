# Facebook-Likes-Counter
Plugin shows dynamically your facebook page likes. I used jQuery to do this.

<b>IMAGE:</b></br>
<img src="http://s6931.chomikuj.pl/ChomikImage.aspx?e=ELZBezrb9C25TdZ1tp8S81eSOfitWy8oD5esyE-6jKb-hyy6xEjeytljjTDjnqVTlfIy3Q7ci-diyiGzHnXayv9gMWJGtNgcyaaZ52aL6Wc&pv=2" />


There are 2 variables which contains <b>YOUR PAGE ID</b> and <b>YOUR ACCESS TOKEN</b>:


        var token = 'YOUR_ACCESS_TOKEN_GETS_HERE';
        var pageId = 'YOUR_PAGE_ID';
        
        
</br>        
<p>If you want to get <b>YOUR_ACCESS_TOKEN</b> you must:</br>
  1) Create your app ( It's preety easy).</br>
      a) Get to: https://developers.facebook.com/ </br>b) Click "MyApps" in the top right corner =>  "Add a New App".</br></br>2) Display Name is your app name ex. "My Access Token". 2nd field is your e-mail.</br></br>3) Now go to your app settings and you will see your <b>"App ID"</b> and <b>"App Secret"</b>. Just copy and paste it to the script:</p>
    
            var token = '{AppID}|{AppSecret}';
           
 </br>        
<b>NOTE:</b> This Access Token is without an expire date, so you can use it every time without change your Access Token. I know it was a               problem for many developers to get lifetime acces token. It's long time expired, I don't think it's lifetime, just saying :) 
</br>
       
 
  And that's it. Run the index.html file. :)
  
  This script can be used ex.for showing yourfans on the TV's in the shopping center.
  
  
