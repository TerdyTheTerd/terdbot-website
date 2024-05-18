# Terdbot Website

> [!IMPORTANT]
> This project is still in active development, nothing is guaranteed to work until a full release is published.

Web portal to manage TerdBot twitch chatbot. Built from scratch, by streamers for streamers. Intergrates with custom Twitch extensions for advanced features not found in any other free chatbots.

https://www.terdbot.com/

![image](https://github.com/TerdyTheTerd/terdbot-website/assets/9743432/326491fe-8924-4f8d-a529-81d4ceb90b6b)

## Features:

- Item Collector:
  - A collection of items with attached images that viewers can collect and trade with each other. Intergrates with an overlay extension for items to randomly appear on screen that viewers can click to collect.

- First Viewer
  - Works with a Channel Point redeem for First Viewer. Offers leaderboards for top viewers and a streak module to reward viewers that are consistently first in your stream.

- Taxes
  - Builds on a Daily Taxes Channel Point redeem to add collected taxes into a prize pool that can be automatically awarded to a random viewer, or manually kicked off. On screen effects for selecting the winning viewer are available.

- On Screen Counters
  - Build in counters with on screen displays and customized styling/animations. Use for Dark Souls/Elden Ring type death counters
 
- Stream Avatars
  - Extension system that adds animated avatars to viewers that can be displayed on stream. An accessory system allows viewers to customize their avatar with purchased or collected accessories. 
 
## Task

- [x] Setup initial web portal with user account creation
- [x] Setup database
- [x] Intergrate Twitch account authentication
- [x] Backend modules for managing database connections, emails and site logging
- [ ] \(In Progress) Create dashboard module with templates for each module
  - [ ] Item Collector template
  - [ ] Taxes template
  - [ ] First Viewer template
  - [ ] Counter template
  - [ ] Song Request template
  - [ ] Random Word template
- [ ] \(Post Release) Stream Avatar Module
- [ ] User settings page with authorization management
- [ ] Chatbot usage analytics (streamer)
- [ ] Site analytics page (admin)
- [ ] Invite module to allow streamers to invite other streamers onboard

## More Info

TerdBot is a passion project of mine to bring some missing features to my stream, and other small streamers twitch streams. Some of these features are meant to be enhanced versions of existing features found in popular chatbots, or free alternatives to more advanced custom add-ons. The creation of this bot mostly stemmed from frustrations with Streamlabs due to how limiting their customization options are for their modules. TerdBot aims to allow greater control over its modules, while integrating multiple features into one seamless experience for the Streamer. TerdBot is currently operating on an Invite Only basis, and will move to an open public project once it's been tested in production by our initial Stream Sponsors. If you would to learn more about TerdBot or get involved with it, please use the contact form found on the website at https://terdbot.com/index.php#contact
