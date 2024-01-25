https://learn.microsoft.com/en-us/aspnet/core/tutorials/signalr?view=aspnetcore-7.0&tabs=visual-studio
https://apexcharts.com/
program.cs---builder.Services.AddSignalR();
shared.Layout.cshtml-<script src="~/js/signalr/dist/browser/signalr.js"></script>
Routing-eg http://servername/{controller}/{action} 
-Home is the Controller segment
-index is Action segment 
Startup.cs or program.cs file is that part of your application .It can called middleware of your application.
user က ဘယ်view ကိုဘဲသွားချင် သွားချင် controller ကိုအရင်လာရတယ်။Controller ကhttp request တွေအားလုံးကို receive လုပ်တယ်။ ပြီးရင် ဘယ်model ကိုselcect လုပ်တယ်၊ သက်ဆိုင်ရာview ကိုပြပေးတယ်
Microsoft.AspNetCore.Mvc ကို inheritance ယူရမယ်/
Controllerထဲမှာရှိတဲ့Action တစ်ခုက view တစ်ခုဘဲသွားနိုင်တယ်။(one to one  mapping)။ default အနေနဲ့ IActionResult ကိုပြန်တယ်။ ကျန်တဲ့ result တွေက 
ViewResult-Html and markup,EmptyResult-no response,ContentResult-Sringliteral,FileContentResult/FilePathResult/FileStreamResult/FileResult-the content of a file,JavaScriptResult,JsonResult,RedirecrtResult-redirection to a new URL
RedirectToRouteResult-anotheraction of same or other controller,PartialviewResult-Returns html from Partial view, 
