# Directoria support build for ticket #7165

This repository distributes a customer-specific Directoria 2.2.12 theme archive. Two unauthorized components found in the supplied theme copy were removed. This is not a general Directoria release or a complete cleanup of the affected WordPress site.

## Download

Download `directoria-2.2.12-clean-ticket-7165.zip` from the [latest release](https://github.com/the-sohan/directoria-support-ticket-7165/releases/latest). The archive contains a `directoria/` folder and can be installed as a WordPress theme package.

SHA-256: `a660266fba000ef160d125d74854b54f397d532e6824192cb19739401a8b10a1`

## Installation and follow-up

Back up the site first. Remove the existing `wp-content/themes/directoria/` directory completely, then install this archive. Copying files over the old directory can leave unauthorized files behind. The site's developer or hosting provider should investigate the rest of WordPress, review access and credentials, and retest links from Google. Replacing the theme alone does not establish that the site is clean.

This package was validated on a local WordPress site. The client's live site was not changed.
