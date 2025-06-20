# Rayhunter
Notes about setting up and using Rayhunter

## What I read
- [Hunting street-level cell phone surveillance with Rayhunter](https://micahflee.com/hunting-street-level-cell-phone-surveillance-with-rayhunter/)
- [Meet Rayhunter: A New Open Source Tool from EFF to Detect Cellular Spying](https://www.eff.org/deeplinks/2025/03/meet-rayhunter-new-open-source-tool-eff-detect-cellular-spying)

## EFF Repo
- https://github.com/EFForg/rayhunter

## What I did
- Bought Orbic RC400L from [eBay](https://www.ebay.com/sch/i.html?_nkw=Orbic+RC400L).  Cost $15, that inlcuded shipping and it had a charging cord and sim card installed.  It was an eBay refurshed item.  The sim card isn't "live".  When the device starts up is says no service found.
- I was working with [Mint Linux](https://www.linuxmint.com/edition.php?id=319), which I had installed on an old laptop.  I didn't need to try and set up dual booting, so the install was fairly easy.
- Download the file to install
- Plugin your Orbic
- From a Terminal window
- Move to download folder `$> cd Downloads`
- Expanded with `$> tar -xvf release.tar`
- Changed to superuser `$> sudo -i`
- You might have to move back to /home/your-user/Downloads
- Install it `$> ./install.sh`

## How to view the captures
- Plugin your Orbic
- From a Terminal window
- Move to download folder `$> cd Downloads`
- Changed to superuser `$> sudo -i`
- You might have to move back to /home/your-user/Downloads
- Start the server  `$> ./install.sh`
- Using a browser view the stats page at `localhost:8080/index.html`

## Misc
- I see one to three file captures per day
- There is no tracking of where I am, so if I moving around and don't look a the device I might not know where exact I got the hit?
- Steps to the software (same with sim card)
- Mattermost 

