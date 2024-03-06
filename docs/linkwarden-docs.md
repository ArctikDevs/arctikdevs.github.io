#Linkwarden Documentation

Linkwarden is a self-hosted, open-source collaborative bookmark manager to collect, organize, and archive webpages.

The objective is to organize useful webpages and articles you find across the web in one place, and since useful webpages can go away (see the inevitability of Link Rot), Linkwarden also saves a copy of each webpage as a Screenshot and PDF, ensuring accessibility even if the original content is no longer available.

Additionally, Linkwarden is designed with collaboration in mind, sharing links with the public and/or allowing multiple users to work together seamlessly.

### Linkwarden Features

- Auto capture a screenshot, PDF, and readable view of each webpage.
- Send your webpage to Wayback Machine (archive.org) for a snapshot. (Optional)
- Organize links by collection, sub-collection, name, description, and multiple tags.
- Collaborate on gathering links in a collection.
- Customize the permissions of each member.
- Share your collected links and preserved formats with the world.
- Pin your favorite links to the dashboard.
- Full text search, filter, and sort for easy retrieval.
- Responsive design and supports most modern browsers.
- Dark/Light mode support.
- Browser extension, managed by the community. Get it [here](https://github.com/linkwarden/browser-extension)!
- Import and export your bookmarks.
- Installable Progressive Web App (PWA).
- iOS Shortcut to save links to Linkwarden.
- API keys.
- Bulk actions.
- And so many more features!

## Overview

Here you'll find a quick overview of Linkwarden.

This is the first screen you'll see right after you create an account:

![Labeled dashboard](https://docs.linkwarden.app/assets/images/labeled-dashboard-9446084f100066b0ce5d3ac794c8b095.png)

### Links, Tags, and Collections

At the core, there are three types of data you're dealing with:

- **Link**: Also known as Bookmark, Webpage, or URL.
- **Collection**: Think of this as a folder, which then can be shared with your team and/or with the public.
- **Tags**: An additional layer of categorization through keywords for individual Links, enabling precise filtering and searching.

Each user can have an unlimited number of Links, Tags, and Collections.

### Difference between Collections and Tags

Simply saying, each Link can only belong to one Collection, but can have multiple Tags. Another difference lies in its sharability, Collections can be shared and collaborated on, but on the other hand Tags are not shareable.

### Dashboard Overview

**Dashboard**

Your Dashboard is your personal space to get a quick overview of all your Links, Collections, and Tags. You can also Pin your favorite Links for easier access.

![Dashboard Overview](https://docs.linkwarden.app/assets/images/dashboard-fb6120b0063ffd012176bfcb520c92c4.png)

## Collections Overview

Collections are basically folders, which then can be shared with your team and/or with the public.

###All Collections

![All Collections](https://docs.linkwarden.app/assets/images/all_collections-defa514e9029c0b66f279d0168c77d3c.png)

### View all Collections
You can view all your Collections by clicking on the "Collections" tab on the top-left of the screen. You can also get an overview of the Collections you have access to from the sidebar.

### View individual Collections
Clicking on the Collection card directs you to the Collection. Below, we have all our Links under the "Health And Wellness" Collection:

![View Individual](https://docs.linkwarden.app/assets/images/single_collection-ae357cb585f175e779783437fbdf0e0f.png)

### Creating Collections

You can add a new Collection by clicking the "New Collection" card in the Collections page.

![Add Collection Modal](https://docs.linkwarden.app/assets/images/add_collection-fa3da4af411963cdadfa98d66da941f9.png)

From there, you can set a Name, Color, and Description for the new Collection right out of the box.

### Sharing a Collection

Click on the top-right of each Collection card to open a dropdown menu for each Collection. From there, click on "Share/Collaborate" to open the Share & Collaboration modal for that specific Collection:

![Share & Collaborate collection tab](https://docs.linkwarden.app/assets/images/share_collaborate_collections-eb1d169cf100eb2b3cbdc72542fdc2fe.png)

### Make a Collection Public

You can share a specific Collection with the world under a specific address by clicking the "Make this a public collection" right under the "Make Public" section.

### Adding a Member

Right under the "Member Management" section, there's a textbox. Fill in the textbox with the username of the user you want to add to your collections.

### Managing the Permissions

There are 3 types of permissions each member can have:

- **Create**: Can create Links under a specific Collection.
- **Update**: Can update Links that are already created by either the owner OR the members who have the permission to "Create" Links.
- **Delete**: Can delete Links that are already created by either the owner OR the members who have the permission to "Create" Links.

### Deleting a Collection

To delete a Collection, click the "Delete Collection" button in the menu for each Collection. Since this action may be triggered accidentally and there's no going back, you are required to enter the Collection name to confirm your request.

![Delete collection tab](https://docs.linkwarden.app/assets/images/delete_collection-2077659d831c353d03eb6da6d3c93201.png)

## Links

Links, also known as Bookmark, Webpage, or URL, is one of the core components of Linkwarden (hence the name).

![All Links](https://docs.linkwarden.app/assets/images/all_links-55346e773fe47d4ee9a0f8d21851ec21.png)

### Adding a Link

You can add a new Link by clicking the "+ New Link" button on the top-right of the screen.

![Add Link](https://docs.linkwarden.app/assets/images/add_link-52265e771f9174f7a791aaaf6673be58.png)

A couple of things to consider:

- The "Address" field is mandatory.
- The "Collection" field is also mandatory, BUT will be set as "Unorganized" if nothing is provided. So a new Collection (named "Unorganized") will be created.
- The "Description" field will be autogenerated based on the webpage title if nothing is provided.
- The "Name" field overwrites the "Description" field while being displayed in the Link card.

### Viewing a link

![View Links](https://docs.linkwarden.app/assets/images/link_details-38677ab5e72850f8ba81b805014e30d5.png)

### Editing a Link

To edit a Link, click on the menu dropdown of the Link and click on "Edit" to open the edit modal.

![Edit Links](https://docs.linkwarden.app/assets/images/edit_link-5be55f9c5f4a43aafa4b737fe6e0e0bc.png)

### Pin a Link to your Dashboard

To pin a Link to the dashboard, click on the menu dropdown of the Link and click on "Pin to Dashboard" to pin the Link.

!!! info "Heads Up!"

	As of now, only Collection owners can pin Links to their dashboard.

### Delete a Link

To delete a Link, click on the menu dropdown of the Link and click on "Delete" to delete the Link.

## Profile Settings

Here you can find a guide for the profile settings.

### Toggle Light mode

If you prefer a light theme over a dark theme, no problem! Simply click on your profile photo at the top-right of the screen and click on "Switch to Light" to see the effects.

![daynight toggle](https://docs.linkwarden.app/assets/images/light_mode_dashboard-d49a50f1e1352c16e9c3c7441d4d0366.png)

### Edit Profile

To edit your Name, Username, or Email, click on your profile photo at the top-right of the screen and click on "Settings" to open the settings modal.

![Edit Profile](https://docs.linkwarden.app/assets/images/profile_dropdown-4f60c5b00d9ff61a2e783447b9ca2045.png)

### Manage visibility

In the second tab of the Settings modal, you can click on the "Make profile private" checkbox, if you click Save, this will immediately prevent access to you profile from anyone.

### Whitelist Specific Users

If you need to collaborate with a friend or colleague while keeping your profile private, you can add their unique username (not display name!) below the checkbox, seperated by comma.

![Whitelist Users](https://docs.linkwarden.app/assets/images/edit_profile-b99a92816da990b9f0652dfb3e422f21.png)

### Import Bookmarks

You can import your data from the settings, the file should be in a "bookmarks HTML file", which is supported by most browsers like Chrome, Brave, Edge, Safari, Firefox and many others...
