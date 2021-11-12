# TIL

Oct 21, 2021
・ All users visiting a site will be assigned a cookie that is store in their browser. If they leave the site then return to  later, the cookie will be used by the site to identify the user who’s been on the site in the past

Oct 22, 2021
・ Core Information inside Cookies: (1) unique user identifier (2) user details. Cookies can also hold various browser-specific attributes on how to manage the cookie itself. (ex how long to keep it).

Oct 29, 2021
・ Oftentimes, cookies are made by the backend(code or webserver) as part of the response through an HTTP header. The HTTP header is named Set-Cookie with a key-value pair (ex. Set-Cookie: myfirstcookie=somecookievalue)

Oct 30, 2021
・ Different types of cookies: 
(1) Session Cookies - temporary and lower security risk, stored in browser memory only, when browser is closed cookie is removed
(2) Persistent Cookies - longer time period and greater security risk, expiration date is set by issuer (ex. Facebook, Google), when browser is closed cookie is NOTED removed
(3) First-Party Cookies - used by online shopping sites, without it, the site would NOT remember previous items in shopping cart and would treat every item added as a new transaction
(4) Third-Party Cookies - generated when a user clicks an ad on a website they are visiting, the cookie associates user traffic with the site that showed the ad

Nov 4, 2021
・ Protecting online privacy: (1) Check browser’s privacy and security settings. Change browser’s cookie policies to meet preferred level of privacy. Take note that cookies make it easier to access certain features on different websites.

Nov 5, 2021
・ Protecting online privacy: (2 ) Browse on Incognito mode. Most modern browsers provide a feature to browse the internet without any cookies. In this regard, when browsing, existing persistent cookies will not be used. Additionally, any persistent cookies created while browsing will be instantly deleted upon closing the browser.

Nov 11, 2021
・ Zombie cookies cannot be deleted using the browser. It is deleted through more technical means

Nov 12, 2021
・ Chrome dev tools > Application > Cookies // see cookies

Novemeber 18, 2021
・ Cookies can travel over AJAX requests. They can be travel back and forth between frontend and backend as long as the frontend and the backend are on the same origin. 
・ An origin consists of a scheme, domain, and port number. http://localhost:8000/ is of a different origin from http://localhost:42091/ (different port numbers)

Novemeber 19, 2021
・ Secure attribute: makes sure that a cookie is never accepted if the connection is NOT HTTPS. Unless the connection is HTTPS, the browser rejects secure cookies.
・ javascript progress bars