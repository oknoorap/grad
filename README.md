# :helicopter: GRAD
GRAD is stands for Git Release Auto Deploy. A WordPress plugin to auto download .zip binary when new tag pushed to git repository.

GRAD will receive webhook request, then webook will trigger to download released binary and upload it to WordPress media.

This plugin is useful for private plugin provider in your theme. For example, if theme is using [TGM Plugin Activation](http://tgmpluginactivation.com/), we must add private plugin's URL in TGM config. 

The development workflow should be as simple as possible. GRAD will be the rescue. We don't need to download zip binary from (private) repository and reupload again to our hosting.

# :computer: Installation
1. Download plugin from [release page](https://github.com/oknoorap/grad/releases).
2. Login to WordPress admin area.
3. Go to plugins > add new (upload).
4. Activate it.

# :rocket: Quick Setup
1. Go to Settings > GRAD.
2. Add private tokens from your git hosting.
3. Setup Webhook URL in your git hosting to http://yourdomain.com/wp-json/grad/v1.
4. Done.

# License
MIT © [oknoorap](https://github.com/oknoorap)
