# Audiobookshelf Documentation

Audiobookshelf is a self-hosted audiobook and podcast server.

## Features
- Fully open-source, including the android & iOS app (in beta)
- Stream all audio formats on the fly
- Search and add podcasts to download episodes w/ auto-download
- Multi-user support w/ custom permissions
- Keeps progress per user and syncs across devices
- Auto-detects library updates, no need to re-scan
- Upload books and podcasts w/ bulk upload drag and drop folders
- Backup your metadata + automated daily backups
- Progressive Web App (PWA)
- Chromecast support on the web app and android app
- Fetch metadata and cover art from several sources
- Chapter editor and chapter lookup (using Audnexus API)
- Merge your audio files into a single m4b
- Embed metadata and cover image into your audio files (using Tone)
- Basic ebook support and ereader
  - Epub, pdf, cbr, cbz
  - Send ebook to device (i.e. Kindle)
- Open RSS feeds for podcasts and audiobooks

## Adding a Podcast

There are two ways to add a podcast to your server:

**Adding through the UI**
You can add podcasts in the UI using the "Add" tab (either in the web interface or the app). You can search by name, RSS link, or upload an OPML file. This is just a general search field; the search terms are not stored anywhere.

![Podcast search results](https://www.audiobookshelf.org/guides/podcasts/security_now_search.png)

Once you have searched for the podcast and added it, you can check for episodes to download. No podcasts are downloaded automatically when you first create the podcast.

**Adding through the File System**
If you already have files for your podcast, you can manually create a directory for the podcast. Note that all files for a podcast must be in the same folder, and subfolders are not yet supported. ABS will parse metadata tags from the podcast files, but this is not well documented yet.

You can use another program or service to get the podcast files and place them in the directory instead of using the integrated ABS downloader.

## Downloading Podcasts
There are several ways to download podcast episodes within ABS. If you want to search for files and pick which ones you want to download, you can use the "Find Episodes" button (magnifying glass button circled in blue below). This presents you with a list of files available from the RSS feed that you can download.

![Find Episodes](https://www.audiobookshelf.org/guides/podcasts/newly_added.png)

You can also ask ABS to download episodes since a certain date. This is done on the "Episodes" tab of the podcast settings. Note that you will need to change the date because it defaults to the current time. You can specify a max number of episodes to download or change it to unlimited.

![Podcast Episodes tab](https://www.audiobookshelf.org/guides/podcasts/episodes_tab_blank.png)

If you would like ABS to automatically check for new episodes to download, you can do this on the "Schedule" tab of the podcast settings. By default, ABS will keep every episode downloaded. If you would like ABS to automatically delete the oldest episode once you have reached a threshold, you can set the max number of episodes to keep.

![Podcast Schedule tab](https://www.audiobookshelf.org/guides/podcasts/schedule_tab.png)

Podcasts marked for download are added to the Download Queue page.

---
## Collections and Playlists

Collections and playlists are another way to organize individual books and podcast episodes (not podcasts).

**Collections and Playlists Features**:

Both Collections and Playlists:
- Are Library specific
- Listening progress is tracked by user (not shared listening state between multiple users)
- Have a description field
- Can be reordered
- Cannot contain groups of things (other playlists/collections, series, etc)
- Have a "Play" button at the top which acts as a "Play All" button

### Collections:

- Are Public. Any user with access to the library can see the contents of the collection
- Can only contain books

### Playlists:

- Are Private. Only the user who created the playlist can see it
- Can contain books or podcast episodes

*Note: Screenshots are from an install of v2.2.0 in Docker. The interface is still pretty much the same, but some buttons have moved slightly. These changes are noted in the text.*

## Creating a Collection or Playlist

### Creating from Library View:
![Initial collection](https://www.audiobookshelf.org/guides/collections/1_no_collections.png)

### Creating from Book Details:
![Collections from library](https://www.audiobookshelf.org/guides/collections/collections_library.gif)

### Adding Podcast to Playlist:
![Add podcast to playlist](https://www.audiobookshelf.org/guides/collections/podcast_add_to_playlist.png)

### Adding to Existing Collection:
![Add to existing collection](https://www.audiobookshelf.org/guides/collections/collection_add_to_existing.gif)

## Editing a Collection or Playlist

### Collections View:
![Collections view](https://www.audiobookshelf.org/guides/collections/2_collection_main_view.png)

### Editing Collection Description:
![Edit collection description](https://www.audiobookshelf.org/guides/collections/edit_collection.gif)

## Roadmap Items

The following items are on the roadmap, in no particular order or expected time to be released:
- Auto adding new podcast episodes to playlists