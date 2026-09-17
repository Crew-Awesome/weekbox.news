Hey guys! Malloy here.

The new WeekBox 2.2.0 ISPR build is ready for Discord users. You can get the build through the [WeekBox Discord server](https://discord.gg/pE89DG8TTA). Join the server to download it, get updates, and share feedback with the team.

This build includes a rebuilt Home page, better GameBanana search, new filters, improved discovery cards, loading changes, security updates, and more work behind the scenes.

## A new Home page

The Home page now uses a new MD3-style carousel with smoother movement and gesture support.

Section titles can also change based on your searches and filters, giving you more useful information while browsing.

We improved the discovery cards, titles, subtitles, and mobile layout too. WeekBox can now show popular mods alongside mods that the community commonly searches for.

## Better search and filters

The homepage and search bar now include a new filter system.

Search is powered by WASE, the WeekBox Advanced Search Engine. It was created to improve how WeekBox finds mods through GameBanana, including the way it retrieves mod data and metadata.

There are also more native HTTP requests and other optimizations behind the scenes. Most of this work is invisible, but it makes WeekBox easier to maintain and gives us a better base for future updates.

## Loading page and security updates

The loading page now stays visible until the rendering engine finishes loading. We also improved the version display, loading messages, and loading statuses.

This release includes protections against future XSS attacks, other security improvements, better documentation, and updated card styling.

## Still in progress

These features are still being worked on:

- Library
- Mod dependencies
- Configurations page
- About page
- Downloads page

They are not ready in this ISPR build yet, but they are still planned for future updates.

WeekBox can run on Windows, macOS, and Linux. On macOS and Linux, installation still requires some technical setup because the app uses a GTK-2 WebView and needs additional licensing and permissions.

## Found an error?

This is an insider build, so you may run into problems while testing it.

If you find something broken, report it in the [WeekBox Discord server](https://discord.gg/pE89DG8TTA) and include `[ISPR Build]` in your ticket or title.

That tag helps us separate reports from the insider build and public versions.

Please do not replace your current build with the ISPR version. This release is a sneak peek, and we are still working on it before the changes move into a public build.

Thanks for testing WeekBox, reporting problems, and helping us improve the launcher.

**Malloy**  
*WeekBox Project Lead*
