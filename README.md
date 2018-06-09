# iploggerfilter
This repo is for uBlock Origin/Adblock Plus and similar blockers to filter any site/subsite who's only purpose is to log your IP

## Installation

### Automatic (Adblock Plus, uBlock Origins)
  Click this [(Subscribe)](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/piperun/iploggerfilter/master/filterlist&title=Piperun%27s%20iplogger%20filter)
  
### Manual (uBlock Origins)

  - Go to uBlock Origins settings
  - Navigate to 3rd-party filters page
  - On the bottom of the page, there should be an textbox where there are a bunch of example urls
  - Copy and paste into the textbox:
  
  ```
  https://raw.githubusercontent.com/piperun/iploggerfilter/master/filterlist
  ```
  
  - Now there should appear a yellow button called "Parse", click it
  - Lastly you need to go to the top and hit the yellow "Update now" button

## Manually updating (uBlock Origins)
It seems ublock can be slow with updating the filter list itself, so if you want to stay up to the latest version as fast as possible you need to manually update it:
  - Go to uBlock Origins settings
  - Navigate to 3rd-party filters page
  - There should be an custom filter named: piperun's iplogger filter
  - Click on the "purge cache" on the right of the name
  - Now there should appear an yellow button at the upper left named: "Apply Changes", click it
  - It should now show the correct amount of filter items


Note: This list is only for any domain name which purpose is only to log your IP and or your browser, such as an site's only clear motive or having it as an hidden unneccesary functionality (like an url-shortener) which can then be distributed to either a customer(s) or user(s) of that site, however if the site specifically makes it clear that it only logs the IP for technical or security reason for the site itself and it doesn't invades people's privacy or security it will most likely not be added.
