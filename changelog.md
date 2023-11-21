# v4.3 (21 November, 2023)
 - ADDED monetization system, users are able now to sell their own content like only fans.
 - ADDED directory system, users can view the site content without the need to login.
 - ADDED the option to choose the default landing page, NewsFeed, Register, Welcome or Directory.
 - ADDED reels system, users can upload their own videos as reels.
 - ADDED watch page, users can view and watch all videos from one page.
 - ADDED qiwi pament method.
 - ADDED payfast payment method.
 - ADDED switch accounts system, user can login to multiple accounts.
 - ADDED the ability for users to create ads in story system.
 - ADDED wordpress login system.
 - FIXED 95+ reported bugs in the system.
 - IMPROVED code in few files.
 - UPDATED few libs in PHP.
 - IMPROVED nodejs chat system speed and code.

# v4.2.1 (19 May, 2023)
 - FIXED contact us page on sunshien theme.
 - FIXED messages list not showing on phone in sunshine.
 - FIXED turn off / on notifications on sunshine theme.
 - FIXED notifications bell not showing on sunshine on profile page.
 - FIXED announcement text not showing on sunshine theme.
 - FIXED comments cannot be made on blogs.
 - FIXED users cannot be verified by moderators.
 - FIXED avatars cannot be changed in manage genders page in admin panel.
 - FIXED sorting by price doesn't work well on marketplace.
 - FIXED creating an article in the blog and publishing it, it does not show words with accented letters.(à,è,ì,ò,ù).
 - FIXED 10+ minor bugs in back and front end.

# v4.1.5 (14 Feb, 2023)
 - ADDED Cache System -> now the website speed is more than 80% faster, average load dropped from 1.2s to 0.15s.
 - FIXED 4 security issues, in follow privacy, bruteforce on login & two auth, XSS in messages using nodejs.
 - FIXED 2+ more minor bugs.

# [DESIGN UPDATE] v2.6.3 (20 Oct, 2022)
 - Fixed some minor issues.

# v4.1.4 (25 Sep, 2022)
 - FIXED slow load when visiting the website first time.
 - FIXED br tag showing on user about, pages, groups and products.
 - FIXED wasabi not working with nodejs.
 - FIXED jpg images with webp mime type returning null images.
 - FIXED videos are playing even though you play another video.
 - FIXED coinbase payment returning to 500 Internet server error when canceling a payment.
 - FIXED profile completion system not working in Instagram mode.
 - FIXED movies cannot be added by moderators.
 - FIXED showing long balance in my earnings page.
 - FIXED post limit per hour not working.
 - FIXED 4+ more minor bugs.

# v4.1.3 (11 Sep, 2022)
 - FIXED funding page design was broken.
 - FIXED sending a not supported file in chat won't show the wrong file format pop up.
 - FIXED when you send a file or an image in chat, clicking on the image doesn't open it.
 - FIXED "now ago" showing on notifications.
 - FIXED files are not being deleted from third party storage after deleting the post.
 - FIXED article link will not open if there an extra slash at the end.
 - FIXED 4+ more minor bugs.

# v4.1.2 (06 Sep, 2022)
 - ADDED new emojis to messages and posts.
 - ADDED drag and drop to upload stories page.
 - ADDED unseen effect to stories.
 - ADDED new video player.
 - ADDED video player for movies.
 - ADDED drag and drop to create an album page.
 - ADDED audio player on chat when sending a recording file.
 - ADDED new dropdown menu on header, post and profile.
 - ADDED new upgrade to pro system. Now users can upgrade to another pro package using the same go pro page instead of using settings page.
 - ADDED new cron-job.php file, (should be added).
 - ADDED ISO system for langs.
 - ADDED Href SEO meta tags.
 - ADDED BACKBLAZE stroage.
 - ADDED the ability to upload files from server directly to third party stroages like S3.
 - ADDED custom endpoint for each storage (CDN support).
 - ADDED new reaction icons.
 - ADDED stories unseen border colored animation (profile page).
 - ADDED 10+ more regions to Wasabi, Ocean and Amazon.
 - ADDED the ability to choose who can use the affiliate system.
 - ADDED the ability to edit forum sections and forum names.
 - ADDED the ability to set custom minimum withdrawal amount.
 - ADDED "Add Photo" button to post publisher box after choosing an image.
 - ADDED Google Translate API for posts.
 - ADDED "Email Deliverability" system to debug and check the log of SMTP settings.
 - ADDED Hindi, Urdu, Chine, Indonesian, Croatian, Hebrew, Bengali, Japanese, Portuguese, Italian, Persian, Swedish, Vietnamese, Danish, and Filipino languages.
 - IMPROVED design / colors in default theme for few sections.
 - IMPROVED code security.
 - REMOVED 10+ unused files.
 - UPDATED loading icon for notification dropdown.
 - UPDATED design of user list in right sidebar in user profile page .
 - UPDATED movies watch page design.
 - UPDATED funding page design.
 - UPDATED date selector for events, profile and other sections.
 - UPDATED user settings page.
 - UPDATED keyboard shortcuts model design.
 - UPDATED header icons.
 - UPDATED "Profile Completion" design.
 - UPDATED page design.
 - UPDATED start-up page.
 - UPDATED chat tab design.
 - UPDATED wallet page design.
 - UPDATED design in few section in sunshine theme.
 - FIXED reply to messages on sunshine theme (nodejs).
 - FIXED video / audio call dialog not closing if there are multiple tabs.
 - FIXED "mark all messages" as read button was hanging.
 - FIXED stickers not working on nodejs.
 - FIXED FTP storage was not working on nodejs.
 - FIXED SEO links on movies, added movie title to movie link instead of using only /ID
 - FIXED showing dollar sign on points page even if you have a different currency.
 - FIXED clicking on "Advanced Search" was redirecting to 404 page.
 - FIXED create blog link could be accessed even if the permission is not allowed.
 - FIXED points were not added if the blog approval system was enabled.
 - FIXED blog is not deleted if you delete the blog post.
 - FIXED Agora live streaming.
 - FIXED Wallet + Balance were showing on "My Earnings" page.
 - FIXED group chat notifications (nodejs).
 - FIXED br tags showing on post title.
 - FIXED video files are not deleting from the server (FFmpeg)
 - FIXED promoted pages/posts were not reset after the pro membership is ended.
 - FIXED 3 nodejs warning messages.
 - FIXED comment is not working when using the french language.
 - FIXED the ability to upload multiple images on the product.
 - FIXED wasabi not working on default east region.
 - FIXED UTF-8 characters not working on games.
 - FIXED "Max Upload Size" not updating from admin panel.
 - FIXED user can upload audio files even if the audio upload is not allowed for the user group.
 - FIXED weather not showing on the sunshine theme.
 - FIXED audio recording upload using nodejs from chat and messages page.
 - FIXED can't post if post approval system enabled from admin panel.
 - FIXED 50+ design and frontend minor bugs.
 - FIXED 10+ more minor bugs.

# v4.1.1 10 Jul 2022
- ADDED story viewed time.
- IMPROVED design / colors in default theme for few sections.
- IMPROVED audio player design.
- FIXED create article issue.
- FIXED pick your plans, go pro plans were not showing on welcome page.
- FIXED CROS issues in nodejs.
- FIXED wallet system was not accepting top ups more than 1000
- FIXED message button was not showing on profile (mobile).
- FIXED {site_name} showing on registration page.
- FIXED charts were not showing on groups and pages if loading using ajax.
- FIXED stories now are ordered by DESC instead of ASC.
- FIXED chat colors, default color was black.
- FIXED birthday showing NULL on profile page sometimes.
- FIXED clicking on stories next shows pervious story.
- FIXED charecter limit on privacy page.
- FIXED disabling pages was disabling the create button on top header.
- FIXED YouTube videos on Instegram mode wasn't working.

# v4.1 10 Jul 2022
- ADDED report user system + reason.
- ADDED ban message on user profile if user is banned.
- ADDED Instagram Mode.
- ADDED flutterwave payment method.
- ADDED Ngenius payment method.
- ADDED Aamarpay payment method.
- ADDED the ability to add custom pro packages.
- ADDED the ability to add custom withdrawal method.
- ADDED the ability to resend two auth verfication code.
- ADDED new design for Instegram mode.
- UPDATED email verfication page design.
- UPDATED chat design.
- UPDATED all website shadow elements (css).
- UPDATED header notifications, messages dropdown size.
- UPDATED post comments design.
- IMPROVED design in default theme for few sections.
- FIXED qrcode.js was missing in sunshine.
- FIXED login using twitter.
- FIXED OG meta tags for albums.
- FIXED XSS vulnerability.
- FIXED fixed product showing in stock while there is no stock left.
- FIXED announcements wern't working.
- FIXED agora live video / calls.
- FIXED google login API.
- FIXED twilio video/audio calls.
- FIXED if post was boosted on a page it doesn't appear in booted posts section.
- FIXED the ability to send gif & stickers on nodejs.
- FIXED 40+ more minor bugs.
- FIXED bugs in API.

# v4.0.1 (23 Feb 2022)
- ADDED audio player for mp3 files.
- ADDED yandex API for maps.
- ADDED yandex payment method.
- ADDED iyzipay payment method.
- ADDED securionpay payment method.
- ADDED authorize.Net payment method.
- ADDED ok.ru social login.
- ADDED new APIs in developers page: get_pages, get_groups, get_products, get_followers, get_following, get_friendsUPDATED design in few sections.
- FIXED price not showing in products.
- FIXED links not working on profile page.
- FIXED ajax load in few pages.
- FIXED broken images when importing a link.
- FIXED add as familly system.
- FIXED XSS vulnerability.
- FIXED 10+ more minor bugs.
- FIXED bugs in API.

# v4.0 (07 Feb 2022) [Ultimate Update]
- ADDED website mode, switch your website instantly to Linkedin mode. (Instagram, Twitter, AskFM, Patreon are coming soon).
- ADDED website mode, switch your website instantly to Linkedin mode. (Instagram, Twitter, AskFM, Patreon are coming soon).
- ADDED marketplace system, users can now buy and sell products
- ADDED moderator rules manager, now you can choose what a moderator can do.
- ADDED more ads placements (jobs, forums, movies, offers & funding) & entire site option.
- ADDED multiple levels affiliate system.
- ADDED custom ban message for every user.
- ADDED the ability to translate terms pages.
- ADDED CoinBase payment method.
- ADDED new search system for Linkedin mode.
- ADDED more APIs.
- ADDED ReCaptcha to create article page.
- ADDED Wasabi Storage.
- ADDED new welcome page.
- ADDED remember me on login page.
- ADDED mutli languages support for terms, privacy and about pages.
- UPDATED bulksms API.
- UPDATED CoinPayments API.
- UPDATED Infobip API.
- UPDATED marketplace, jobs & movies pages design (default theme).
- UPDATED desgin in a few other pages (default theme).
- UPDATED Twilio SDK.
- UPDATED left sidebar icons. (default theme)
- UPDATED documentation & FAQs: https://docs.wowonder.com/ .
- CLEANED 10,000+ lines of outdated code.
- ORGINZED PHP code format (HTML coming in next update).
- FIXED images with _small extensions is not getting deleted on remote storage.
- FIXED watermark isn't working on images posts.
- FIXED family memebers texts.
- FIXED auto username, pages likes or groups joins isn't working when you register using the app.
- FIXED login with instagram isn't working.
- FIXED email notifications are not working on follow, view profile or comments.
- FIXED Audio/video calls are not working from website to apps using agora.
- FIXED "common things" page php fatal error.
- FIXED 2 XSS exploits. [Important!]
- FIXED blank page when adding / in url.
- FIXED site-map doesn't generate more than 50K links.
- FIXED read more button on mobile.
- FIXED 30+ more minor bugs.
- FIXED bugs in API.

# v3.2.2 (09 Augest 2021)
- ADDED Palestine to country list.
- REMOVED dublicated nginx rules in nginx.conf, update required for nginx users.
- REPLACED Yahoo weather with new provider https://openweathermap.org
- FIXED live video not working on firefox.
- FIXED blog point issue, user will get points now after approving.
- FIXED nearby shops counter.
- FIXED line break issue in nodejs chat system.
- FIXED refund page wasn't apearing.
- FIXED issues in desgin.
- FIXED video post on MySQL 8 and PHP 8.
- FIXED more minor bugs.
- FIXED bugs in API.

# v3.2.1 (28 June 2021)
- FIXED seen issue on nodejs.
- FIXED FTP support on nodejs.
- FIXED "View X Posts" on newsfeed (NodeJS).
- FIXED 2 security issues (important).
- FIXED double points when posting multi images.
- FIXED 500 Error when accessing a page without being logged in.
- FIXED URL fetcher, it wasn't fetching URLs from WoWonder blogs.
- FIXED bugs in API.

# v3.2 (8 June 2021)
- ADDED expire time for reset password links, 12 hours.
- ADDED auto username generator, for new user registration users are not required to write their username. (Enable / Disable)
- ADDED new APIs, more than 40+.
- ADDED reactions for messages, (ajax / nodejs).
- ADDED reply system for messages, (ajax / nodejs).
- ADDED reactions system for stories.
- ADDED reply system for stories.
- ADDED gifs + stickers to comment system.
- ADDED gifs + stickers to reply system.
- ADDED video chat by Agora.
- ADDED terms of use checkbox to contact us page.
- ADDED the ability to delete poll answers while creating one.
- ADDED login with Mailru, Discord, WeChat and QQ.
- UPDATED twilio video chat system.
- UPDATED message seen systemn (NodeJS).
- FIXED 80+ reported bugs and improvments.
- FIXED bugs in API.

# v3.1.3 (12 April 2021)
- ADDED real-time notification system.
- IMPROVED server load & site speed.
- REMOVED All PHP ajax intervals, requests, and loops from clinet end (if nodejs enabled) and replaced to realtime web socket.
- FIXED 3+ reported bugs.
- FIXED bugs in API.

# v3.1.2 (28 March 2021)
- ADDED support for PHP 8.0+ and MySQL 8.0
- UPDATED nodejs chat system, now users can see typing action on messages user list, real time avatar update, name, and status.
- UPDATED S3 / Spaces libraries.
- IMPROVED speed on PHP 8.0
- FIXED 20+ reported bugs.
- FIXED bugs in API.

# v3.1.1 (05 March 2021)
- FIXED 10+ reported bugs.
- FIXED bugs in API.

# v3.1 (04 March 2021)
- ADDED new messaging system powered by NodeJS and websockets, now chat are faster, real time, and smoother.
- ADDED new timestamp system, e.g (1 mintue ago -> 1 m, 2 hours ago -> 2 hrs, 1 month ago -> 4 w, 1 year ago -> 1 y)
- IMPROVED security. [Important]
- FIXED 60+ reported bugs.
- FIXED bugs in API.

# v3.0.3 (08 July 2020)
- ADDED ability to choose camera on live streaming.
- ADDED thumbnail for live streaming videos.
- ADDED female avatar for female users.
- ADDED Few more APIs. (payment methods)
- FIXED 20+ reported bugs.
- FIXED bugs in API.

# v3.0.2 (26 May 2020)
- ADDED Agora Live Streaming.
- ADDED Few more APIs.
- FIXED 40+ reported bugs.
- FIXED bugs in API.
- IMPROVED Load speed.

# v3.0.1 (18 April 2020)
- FIXED 10+ bugs.
- FIXED bugs in API.

# v3.0 (16 April 2020 [Ultimate])
- ADDED the ability to edit/add/disable post reactions.
- ADDED memories system, user can view his memories on this day.
- ADDED live stream for posts [enable/disable] (third party sites).
- ADDED page analytics, view latest likes per week, month, year, and today.
- ADDED group analytics, view latest joins per week, month, year, and today.
- ADDED blog post notifications, get a notification when someone comments on your blog post.
- ADDED forum notifications, get a notification when someone comments on your forum thread.
- ADDED the ability to require membership on sign up, [enable/disable]
- ADDED sub categories for pages, groups and marketplace.
- ADDED custom fields for pages, groups and marketplace.
- ADDED remaining pro membership days announcement.
- ADDED recurring payments for pro system.
- ADDED the ability for only pro users could upload [enable/disable].
- ADDED the ability for only pro users could make calls [enable/disable]
- ADDED blog posts review/approval system.
- ADDED the ability to request refund for pro package [enable/disable]
- ADDED refund policy page.
- ADDED paystack, razorpay, paysera and cashfree payment methods.
- ADDED page to show shops/businesses nearby.
- ADDED offer system for pages.
- ADDED password complexity system on register page.
- ADDED prevent brutforce on login system, limit failed login per min.
- ADDED the ability for users to be able to post in the pages. [enable/disable]
- ADDED the ability for pages and groups owners could add moderators with certain privileges.
- ADDED google cloud for storage.
- ADDED email mock system. send email for users who didn't login for X time.
- ADDED the ability to add games from other sites, not just miniclip.
- ADDED the ability to get notified when user posts new post.
- ADDED ads within and inside articles.
- ADDED the ability for users to generate invite links.
- ADDED shout box, post anonymously.
- ADDED the ability to get notified when a friend posts a new post.
- FIXED 50+ bugs.
- FIXED bugs in API.
- FIXED Important security issues.

# v2.5.2 (7 Jan 2020 [Important])
- ADDED click button to comment and reply.
- FIXED bugs.
- FIXED bugs in API.
- FIXED Important security issues.

# v2.5.1 (17 Dec 2019 [Important])
- ADDED view joined groups and liked pages from one page.
- ADDED the ability to attache photos in commment replies.
- ADDED missing files from v2.5
- FIXED bugs in API.

# v2.5 (16 Dec 2019 [Script improvments update])
- ADDED the ability logout from all sessions.
- ADDED the ability to approve or decline a post, enable / disable.
- ADDED new APIs.
- ADDED auto like for pages and auto join for groups.
- UPDATED PHP libaries.
- UPDATED Google login API.
- IMPROVED default theme desgin.
- IMPROVED speed.
IMPROVED english in some parts.
FIXED 100+ reported bugs and issues.
FIXED bugs in API.

# v2.4 (01 Sep 2019)
ADDED the ability to send messages to pages.
ADDED the ability to accept or decline a group chat invitation.
ADDED job system, users can now create jobs and hire.
ADDED weather plugin to sidebar.
ADDED common things page, now you can find users that matches your information.
ADDED funding system, users can create funds, and get paid.
ADDED new APIs.
FIXED 20+ reported bugs.
FIXED bugs in API.
IMPROVED speed.

# v2.3.3 (11 July 2019)
ADDED few new APIs to v2.
FIXED 20+ reported bugs.
FIXED bugs in API.
IMPROVED script stabilitiy for v2.4
IMPROVED speed.

# v2.3.2 (20 June 2019)
FIXED 20+ reported bugs.
IMPROVED speed.

# v2.3.1 (2 June 2019)
FIXED 10+ reported bugs.
FIXED security issue.

# v2.3 (30 May 2019)
ADDED the ability to comment on albums, and multi images.
ADDED filter comments, top and latest.
ADDED the ability to make forums, marketplace and events public and reachable by google.
ADDED the ability to enable / disable PayPal payment method.
ADDED the ability to disable a language without deleting it.
ADDED the ability to enable / disable pokes, and "good monring" message.
ADDED the ability for users to make comment on post before sharing it.
ADDED the ability to block a domain from email while siging up, example, blocking @gmail.com
ADDED embeded product style to messages.
ADDED colored posts, with the ability to manage, add, remove and edit them.
ADDED 2Checkout payment method.
CHANGED password hash from sha1 to password_hash encryption.
IMPROVED ajax speed by reducing requests.php file size and seperating the requests.
FIXED 20+ reported bugs.
FIXED API issues.
FIXED security issue.

# v2.2.2 (12 April 2019)
ADDED deepsound embed feature, now you can embed the player from deepsound to wowonder.
FIXED 20+ reported bugs.
FIXED security issue.

# v2.2.1 (6 April 2019)
ADDED support for PHP 7.3+
FIXED 30+ reported bugs.

# v2.2 (1 April 2019)
ADDED The ability to earn points by creating blogs.
ADDED points daily limit for pro and free users.
ADDED The ability to edit group chat info and avatar.
ADDED The ability to turn off messages from friends or everyone.
ADDED the ability to filter porn and nude pictures using Google Vision API.
ADDED user will require to verfiy his email if he changed is from settings page, if email verfication is enabled.
ADDED new sharing system, with new style and the abiltiy to share to timeline, group and pages.
ADDED the ability to manage pro packages name, icon, features, prices, and disable which one of them
ADDED the ability to view the reactions, likes, dislikes on comments and replies.
ADDED the ability to view reactions, likes of posts on new model.
ADDED bank payments for wallet and pro.
ADDED group chat API, albums API, Pokes API and few other APIs.
ADDED group chat notifications.
ADDED recaptcha to contact us from.
ADDED new message page desgin for default theme.
FIXED few important bugs.
FIXED secuity threat, URGENT an update is required.

# v2.1.1 (29 January 2019)
ADDED Download my information, user can download personal info, pages, groups, posts and friends.
FIXED few important bugs.

# v2.1 (20 January 2019)
ADDED new theme, "sunshine".
ADDED new story system for both themes.
ADDED filter system on marketplace, on the new theme.
ADDED hashtag posts count, on new theme.
FIXED few bugs.

# v2.0.3.1 (30th Octobar 2018)
FIXED few important bugs in wallet system and other major bugs.
v2.0.3 (16th Octobar 2018)
ADDED confirmation system when user login from new location.
ADDED two-factor authentication system using email or phone.
FIXED few bugs.

# v2.0.2 (9th Octobar 2018)
ADDED new video player.
ADDED the ability to disable / enable google maps.
ADDED IP to session manager.
ADDED the ability to disable / enable comments on each post.
FIXED 9 reported bugs.

# v2.0.1 (5th Octobar 2018)
FIXED 11 reported bugs.
IMPROVED Script speed.
FIXED important security vulnerability.

# v2.0 (30th Sep 2018)
ADDED digitalocean spaces storage.
ADDED poke system.
ADDED reaction system (Like, Haha, wow, angry, love).
ADDED gift system, users can send each other gifts.
ADDED statics and charts to daily ads views / clicks.
ADDED Infobip to SMS providers.
ADDED stripe to wallet system like on go pro page.
ADDED password recovery by phone number.
ADDED estimated user reach on create ads page.
ADDED bitcoin (coinpayments) payment method for ads and pro system.
ADDED Payment Transactions history for wallet topups and pro system, with the ability to turn this feature on or off.
ADDED the option to change the phone number from settings page.
ADDED popular posts page.
ADDED photos & videos sections to profile.
ADDED End video chat button.
ADDED ability to use percentage in the affiliate system.
ADDED telegram to share options.
ADDED more emojies.
ADDED shortkey for posts, clicking "j" to scroll to next post.
ADDED points system, user can earn points for posts, comments, likes, dislikes, wonders, and reactions. (User can spend points on pro or ads, or he can requst them as dollars).
ADDED stickers to chat and messages.
ADDED rotate system for images.
ADDED Advanced search system for custom fields.
ADDED Added filter by age, and verfied to the search system.
ADDED suggested groups / pages in my groups and my pages.
ADDED search system in blog.
ADDED auto friend system (Auto follow / friend with new registred users).
ADDED the ability to view mutual friends from the profile (friends system).
ADDED the ability to know who viewed your stories via notifications.
ADDED ReCaptcha check to forgot password form (secuirty).
ADDED blog comment notifications.
ADDED Email notification when the user's account was deleted.
ADDED a warning message before unfriending someone.
ADDED session manager (users can view / manage browser / platforms where they are logged in).
ADDED notification management system (Users can choose what kind of notifications they want to get).
ADDED activities system, user can view his own activities from his profile (like, dislike, react, wonder, comment, reply, follow, friends).
ADDED the ability for a user to choose if their profile should be found/indexed by search engines.
IMPROVED load speed.
COMPRESSED JS files to few less files.
FIXED bugs on API.
FIXED major bugs in the script. (+10)
FIXED 3 security issues.

# v1.5.6.2 (27th Jun 2018)
ADDED New welcome page for the default theme.
ADDED Wasabi storage support.
UPGRADED PHPMailer to v6.
FIXED 10+ reported bugs.

# v1.5.6.1 (13th Jun 2018)
ADDED Day status to default theme (good morning etc).
IMPROVED wonderful theme desgin and forms.
IMPROVED publisher box stability.
REMOVED Weather plugin from wonderful theme due copyright issues.
FIXED 10+ reported bugs.

# v1.5.6 (27th May 2018)
ADDED FTP client server to store files, images, videos on other servers.
ADDED GDPR compliance (cookie frame, checkboxes, privacy policy)
ADDED full new APIv2 + docs.
ADDED the abilty to post mobile emojies on posts, comments, and messages.
ADDED Auto delete system for users and posts that are longer than X date.
ADDED Crop system for user avatar.
TRANSLATED all page's titles.
IMPROVED load post speed on wonderful theme.
FIXED 3 security issues.
FIXED 50+ reported bugs.

# v1.5.5.3 (17th April 2018)
ADDED two keys for OneSignal.
ADDED video call API for mobile applications.
IMPROVED the cache system for user data.
FIXED all reported bugs.

# v1.5.5.2 (6th April 2018)
IMPROVED content load and server load 50% faster.
FIXED all reported bugs.

# v1.5.5.1 (29th March 2018)
FIXED facebook / google login issues.

# v1.5.5 (20th March 2018)
ADDED new theme (default).
FIXED issues & high security vulnerability.

# v1.5.4.3 (30th January 2018 (Important update!))
FIXED issues & high security vulnerability.

# v1.5.4.2 (4th January 2018)
ADDED Indian currency.
ADDED new API for movies, stories.
FIXED 7+ important reported bugs.
SCRIPT stability checkout.

# v1.5.4.1 (22th December 2017)
ADDED Cache-Control to Amazon hosted files.
FIXED 5+ important reported bugs.

# v1.5.4 (13th December 2017)
ADDED the ability for users to send money to each other using their wallet balance.
ADDED Email messages notification for offline users.
ADDED the ability to import images from links in post system.
ADDED profile percentage system. (Fill your profile details for new users).
ADDED new ads placed in the ads system (Users can create ads on videos posts).
ADDED Iframe support for the forum Editor.
ADDED share to wowonder button to blogs.
ADDED the ability for users to choose a default thumb when uploading a video in publisher box.
ADDED playtube video player integration.
CHANGED video player to mediaelement.js
EXPIRED events will be deleted automatically.
CHANGED the blog system design.
FIXED 7+ reported bugs.

# v1.5.3.2 (15th November 2017)
ADDED more regions to Amazon S3.
ADDED explore link to left sidebar.
FIXED 15+ reported bugs.

# v1.5.3.1 (21th October 2017)
ADDED custom currency for the ads system.
ADDED web push notifications.
FIXED 10+ reported bugs.

# v1.5.3 (1st October 2017)
ADDED push notification system for all site notifications.
ADDED the abiltiy to disable wonder/dislike buttons.
ADDED new API files, find friends, events, stories create groups pages and events.
ADDED support for Opera mini and UC browsers.
FIXED 15+ reported bugs.

# v1.5.2 (4th September 2017)
ADDED privacy option for users “Share my location with public?”.
ADDED friends stories to home page.
USER now can view his own ads.
ADDED the option to upload images to blog system.
ADDED multi currency in classified.
ADDED video chat API for the windows application.
ADDED ads prices in craete ads page.
IMPROVED the ads view design.
USER can't create ads if wallet is empty.
FIXED 40+ reported bugs / improvements.

# v1.5.1 (27th August 2017)
FIXED all reported bugs.

# v1.5 (24th August 2017)
ADDED advertisement system. (Clicks, impressions)
ADDED story system. (status, automatically gets removed after 24 hours).
ADDED new comment system for blogs and movies.
ADDED group chat system.
ADDED the ability to edit comment's replies.
ADDED hide posts feature.
ADDED 30+ more emojis.
ADDED full verification form (ID, photo, description).
ADDED new post sharing system.
ADDED sitemap generator.
ADDED registration invite system (Users can register just with invite link).
ADDED new albums style (Collapsed).
ADDED the ability to choose specific users in Mailing List.
ADDED the ability to enable/disable ads system, story system.
ADDED "Who can see my friends" privacy option.
ADDED multi date formats support.
ADDED the ability to lose the verification if the username was changed.
ADDED youtube/video link support for movies system.
ADDED gifs using "Giphy" API for messages/posts.
ADDED API support for upcoming IOS application.
ADDED Lightbox for images on messages, comments, and replies.
ADDED page rate system, users can rate page from 0/5.
ADDED report system for profiles, pages, and groups.
ADDED new API for the new powerful windows desktop application.
ADDED family members list (add a friend as a brother, father etc..)
ADDED relationship assignment, e.g: Lisa is in a relationship with Zach
ADDED find friends nearby (find friends near you within 100KM).
ADDED alert feedback if file mime type/extension is not supported.
ADDED alert if the file is larger than the max allowed size in publisher box, messages and chat.
UPGRADED Password hash system from MD5 to SHA1
CHANGED the trending system to be updated weekly.
UPDATED font-awesome library.
UPDATED emojis library.
FIXED bugs on API.
FIXED major bugs in the script. (+30)
IMPROVED load speed.
FIXED 2 security issues.

# v1.4.5.2 (18th June 2017)
ADDED audio recording to Post/Comment systems.
UPGRADED the API to the newest version for the new android messenger update.
FIXED bugs in the script.

# v1.4.5.1 (6th June 2017)
ADDED movies system.
ADDED translate system for posts.
ADDED video views system.
FIXED twilio SMS bug.
FIXED bugs in the native app API.
FIXED few bugs in the script.
v1.4.5 (25th May 2017)
ADDED forum system.
ADDED events system.
ADDED "Login with WoWonder" API feature + applications + documentation.
ADDED "load more" button to the advanced search page.
ADDED "Share to wowonder" button for third-party websites + documentation.
ADDED custom chat colors for each conversation.
ADDED push notifications support for Android messenger.
FIXED video/audio call bugs.
FIXED bugs in the native app API.
FIXED few bugs in the script.

# v1.4.4.5 (11th April 2017)
ADDED blog system.
FINAL release for full API system (for native apps).
FIXED few bugs.

# v1.4.4.4 (2nd March 2017)
ADDED auto-updater system.
ADDED windows server rewrite URL support (web.config).
FIXED few bugs in the API.

# v1.4.4.3 (23th February 2017)
IMPROVED the script theme.
UPGRADED jQuery library.
INCREASED script speed.
FIXED few bugs in the API.

# v1.4.4.2 (10th February 2017)
UPDATED API for IOS messenger.
FIXED few bugs in the script.
FIXED few bugs in the API.

# v1.4.4.1 (27th January 2017)
UPDATED Hybridauth library (Facebook login bug).
FIXED more than +3 other bugs.

# v1.4.4 (11th January 2017)
ADDED "Read more" to product description.
ADDED custom currency option for classified.
UPDATED PHPmailer library (Security bug).
UPDATED Hybridauth library (Google+ login bug).
FIXED "copyright" text in footer.
FIXED RTL design problems.
FIXED UTF-8 issues in hashtag system.
FIXED JavaScript code bugs in Apple products.
FIXED Android / Windows messengers API requests.
FIXED more than +5 other bugs.

# v1.4.3 (8th December 2016)
ADDED the ability to translate custom fields.
ADDED audio calls.
ADDED integration with the new WoWonder Android Messenger.
ADDED the ability to manage pro membership periods.
ADDED a button to manage and cancel expired pro users.
ADDED Twilio API for sending SMS messages.
ADDED android API for the upcoming native apps.
ADDED Alipay to Stipe.
ADDED hashtag post streaming.
ADDED YouTube field to page social link settings.
ADDED location field to classified system.
IMPROVED database structure.
IMPROVED SQL queries.
IMPROVED script speed.
DESIGN/CODE optimization.
FIXED bugs in messages system.
FIXED few bugs.

# v1.4.2 (10th October 2016)
ADDED Amazon S3 integration.
ADDED the ability to delete full conversations.
ADDED the ability to delete recipient messages.
ADDED Nginx support.
FIXED an issue in login system.
FIXED few more bugs.

# v1.4.1 (3rd October 2016)
MORE than 10+ old and new bug fixes.
DESIGN/CODE optimization.

# v1.4 (25th September 2016)
ADDED new welcome page.
ADDED custom fields system.
ADDED classified system.
ADDED full affiliates system + payments.
ADDED poll system.
ADDED custom pages system.
ADDED more payment methods, (Credit card, Bitcoin, american express).
ADDED YouTube field to social links.
ADDED integration with the new Windows Desktop Messenger.
ADDED new posts updater system (Like twitter).
ADDED image on comments system.
ADDED full messaging API code for windows / Android / IOS.
ADDED CSRF protection for more forms / ajax requests.
ADDED terms link to registration page.
ADDED the option to enable/disable notification sound.
ADDED the option for user to filter posts by all or following.
ADDED more ad placements (between posts).
ADDED 'latest products' placement in sidebar.
ADDED longer user session time.
ADDED new design for messages system.
ADDED custom backgrounds for pages.
REPLACED the URL scrape system with better one.
RE-CODED style.css file to .scss for easy coding and outputting.
SPEED/DESIGN/CODE optimization.
FIXED Hashtag issues.
FIXED birthday privacy issue.
FIXED image rotation issue.
FIXED image cropping issues.
FIXED session hijacking security.

# v1.3.4 (27th June 2016)
FIXED all reported bug.
INCREASED the script speed by 50%.
DESIGN/CODE optimization.
UPGRADED the image optimization system to next level.

# v1.3.3 (19th June 2016)
ADDED video call/chat system for all devices.
ADDED the option to view all posts or following posts.
ADDED the option to enable/disable "developers" page.
ADDED the option to enable/disable user registration.
ADDED "maintenance_mode" to shut down the whole site.
ADDED the option to send mailing list to "active, inactive, all" users.
ADDED dropdown menu for messages button in header.
ADDED gender field for Facebook social login.
ADDED "eapi link" for sending SMS.
ADDED multi chat tabs (max 3 tabs).
ADDED CSRF protection for few more forms.
UPGRADED chat system + messages.
UPDATED API to v1.3.1
FIXED few bugs.
SPEED/DESIGN/CODE optimization.

# v1.3.2 (17th May 2016)
ADDED the ability enable/disable games, pages, groups.
ADDED more currency types for payments, (RUB, PLN, ILS, BRL).
ADDED pull to refresh to android application.
ADDED test log for PayPal configuration.
SPEEDED up loading time.
FIXED redirection issue, (www or without www).
FIXED default language on sign up.
FIXED common bugs.
SCRIPT optimization.

# v1.3.1 (24th April 2016)
ADDED more currency types for payments.
ADDED Portuguese language.
ADDED send button to comment field. (On mobile)
FIXED common bugs.
FIXED security bugs.

# v1.3 (21th April 2016)
ADDED SMS verification system (verify user by phone number).
ADDED premium members (Star - Hot - Utlima - Vip) with PayPal / credit card integration.
ADDED Android, IOS, and Windows Phone apps (web-view).
ADDED cover re-position feature.
ADDED birthday events on home page.
ADDED the ability to boost posts & pages with monthly payments.
ADDED post limit p/ hour for every user.
ADDED registration limit p/ hour for every IP.
ADDED custom CSS file for every user (user can completely re-design his own profile).
ADDED Video.JS/Audio.JS for video & audio players.
ADDED new speed for all action, (follow, add friend, chat, like, dislike, wonder, join etc ..).
ADDED desktop notifications for Google Chrome / FireFox.
ADDED the ability to upload .mov, .flv, .mpeg Videos.
ADDED CSRF protection for common forms.
ADDED send button to messages.
ADDED top featured users bar (applying by paying).
ADDED invite system.
ADDED og-Meta tags for social sharing.
ADDED new loading system (loading content without refreshing the page) & bandwidth saver system.
ADDED new E-mail notification system.
ADDED block system.
ADDED new sources for games importing.
OPTIMIZED layout.
SPEEDED up SMTP.
REPLACED cache system.
REMOVED /welcome from welcome page URL.
UPDATED API to v1.3.
SCRIPT & code optimization.
SEO optimization.
IMPROVED chat system usage of resources.
INCREASED site security (XSS, CSRF, SQL, Spams).
FIXED default country (USA).
FIXED common bugs.

# v1.2.3 (26th February 2016)
ADDED SMTP server.
Added Login with username or email.
FIXED major bugs.
IMPROVED Security.

# v1.2.2 (29th January 2016)
ADDED auto suggestion for mentions in publisher box, comments, replies.
ADDED Start up pages (Add photo, Fill some information, Follow users).
ADDED site design colors to email notification.
ADDED user profile privacy for non-logged users.
ADDED smiles button to comment, send message boxs.
ADDED installer for easy installation.
FIXED Bugs from your feedback.
SCRIPT Optimization.
IMPROVED Speed.
IMPROVED Security.

# v1.2.1 (12th January 2016)
ADDED words wonder, dislike, like to the post action buttons.
ADDED the ability to just like or dislike. (can't do it both).
RE added emotions to post publisher box.
OPTIMIZED chat requests.
FIXED bugs from your feedback.

# v1.2 (10th January 2016)
ADDED group system
ADDED game system
ADDED dislike button (wonder or dislike)
ADDED new lightbox
ADDED login via Instagram
ADDED verification request system
ADDED photo album system
ADDED multi photos upload
ADDED autoload system for posts
ADDED new search system
ADDED recent searches
ADDED page invitation system
ADDED group invitation system
ADDED ban ip system
ADDED feelings/travailing/watching/playing/listening post status
ADDED call to action system for pages
ADDED location autocomplete for user/page setting
ADDED recent searches
ADDED notification popup
ADDED profile visit privacy
ADDED last seen privacy
ADDED profile birthday privacy
ADDED auto detector for Youtube, Dailymotion, Vine, Vimeo, Facebook videos & soundcloud links.
ADDED https support
ADDED comment replies system
ADDED comment auto detector
ADDED education to user profile information
ADDED the ability to like/dislike/wonder/comment on user's profile picture & cover image
ADDED email notification setting
ADDED ip address field to manage users page
ADDED new language (Italian)
REMOVED "@" from user profile URL
REMOVED "p/" from page URL
REMOVED "/home" from home page URL
CHANGED the entire user/page/group setting layout
IMPROVED user popover
IMPROVED layout
IMPROVED layout on smartphones
IMPROVED chat system
IMPROVED site security
IMPROVED link preview
IMPROVED cache system to a higher level
UPDATED API version to v1.1
SCRIPT optimization
BUG fixes

# v1.1 (8th December 2015)
- ADDED Page System.
- ADDED Link Preview.
- ADDED User Typing System & Message "Seen" System.
- ADDED Profile Custom fields (Work, Company, Relationship, Location .. etc).
- ADDED Profile Google Map location.
- ADDED Profile Background image. (user can choose his own background image).
- ADDED Facebook, Vimeo, Dailymotion videos.
- ADDED User Details On Hovering on user link.
- ADDED Censored Words System.
- ADDED 4 New Languages (Dutch, German, Spanish, French).
- ADDED Search Posts System.
- ADDED HTML Support For Announcements.
- CHANGED Welcome Page Style.
- CHANGED Sidebar Style.
- IMPROVED Layout & Styles.
- IMPROVED Layout On Smartphones.
- ADDED More features for Sending emails to all users.
- SCRIPT Optimization.
- FIXED Bugs.
- IMPROVED Security.

# v1.0
- Initial release.
