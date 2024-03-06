# PhotoPrism Documentation

PhotoPrism is a robust open-source photo management solution that offers powerful tools for organizing, searching, and sharing your photo collections. Here's an overview of its features and functionalities:

## Features

1. **Automatic Tagging and Indexing:** Utilizes advanced machine learning algorithms to automatically tag and index your photos based on content, including objects, faces, and scenes, making them easily searchable.

2. **Smart Browsing:** Provides an intuitive interface for browsing through your photo library, allowing you to filter photos by tags, dates, locations, and other metadata.

3. **Facial Recognition:** Recognizes faces in photos, allowing you to easily find all photos containing specific individuals.

4. **Geotagging:** Automatically adds location data to your photos, enabling you to organize and search for photos based on where they were taken.

5. **Cross-Platform Support:** Works seamlessly across various devices and platforms, including desktops, smartphones, and tablets.

6. **Privacy-Focused:** Prioritizes user privacy by offering self-hosting options, ensuring that your photo collections remain private and secure.

7. **Sharing and Collaboration:** Allows you to share albums and collaborate with others by generating shareable links or inviting them to access your PhotoPrism instance.

## Who It's Good For

- **Photographers:** Ideal for professional photographers and enthusiasts who need efficient tools for managing large photo collections.
  
- **Families:** Perfect for families looking to organize and share their cherished memories across generations.
  
- **Hobbyists:** Suited for hobbyists and amateurs who want to keep their photo collections organized and easily accessible.

---
## Albums

### Create New Album

1. Go to Albums
2. In the upper right corner, click 

   ![Screenshot](https://docs.photoprism.app/user-guide/organize/img/create-album-light.jpg)

3. A new album with the name "Month Year" is created

   ![Screenshot](https://docs.photoprism.app/user-guide/organize/img/album-name-1-light.jpg)

### Edit Album Details

**Go to Albums and open the album edit dialog**
=== "From Title"
   
	Click on the album title
   
   	![Screenshot](https://docs.photoprism.app/user-guide/organize/img/album-edit-title-light.jpg)

	 Edit album details and click save

   	![Screenshot](https://docs.photoprism.app/user-guide/organize/img/album-edit-light.jpg)

=== "Context Menu"

	Select album, open context menu and click :material-pencil:

	![Screenshot](https://docs.photoprism.app/user-guide/organize/img/album-edit-menu-light.jpg)

	Edit album details and click save

	![Screenshot](https://docs.photoprism.app/user-guide/organize/img/album-edit-light.jpg)

=== "Album Toolbar"

	Open album and click  :material-pencil: in the upper right corner

	![Screenshot](https://docs.photoprism.app/user-guide/organize/img/album-edit-toolbar-light.jpg)

	Edit album details and click save

	![Screenshot](https://docs.photoprism.app/user-guide/organize/img/album-edit-light.jpg)



### Add Photos to Album

1. Select photos and videos
2. Click context menu
3. Click 

   ![Screenshot](https://docs.photoprism.app/user-guide/organize/img/add-photo-album-1-light.jpg)

4. Select album

   ![Screenshot](https://docs.photoprism.app/user-guide/organize/img/add-photo-album-2-light.jpg)

5. Click add to album

   ![Screenshot](https://docs.photoprism.app/user-guide/organize/img/add-photo-album-3-light.jpg)

!!! tip

	You can select many photos at once using shift.

### Remove Photos from Album

1. Go to your album
2. Select photos/videos you want to remove
3. Click context menu
4. Click 

   ![Screenshot](https://docs.photoprism.app/user-guide/organize/img/remove-from-album-1-light.jpg)

---
## People

### Face Recognition
Our latest version includes facial recognition that lets you find pictures of your family and friends. Be ready to discover long forgotten shots! New faces are detected as you scan your library. They are then grouped by similarity, so you can quickly match them to people.

!!! note

	Recognition does not start until your library has been fully scanned. Searching and updating faces temporarily causes a high CPU load and may take a while, depending on your hardware and the number of images you have.
	
	Existing clusters are automatically optimized in the background, for example, when new faces are detected, you have reported a bad match, or new files are added to your library.

### Recognized & New People

The people section shows you recognized people as well as new face clusters.

To star a person, click the star icon. Starred persons appear first.

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/recognized-new.jpg)
![Screenshot](https://docs.photoprism.app/user-guide/organize/img/new-new.jpg)

### Why doesn't the New Faces page show all faces?

The 'New Faces' page only shows automatically recognized face clusters, as there may be thousands of unknown faces in your library, including random movie actors or faces on shampoo bottles.

You can use the `face:new` search filter to find images with unknown people. We recommend combining this filter with other filters like year or location when searching for specific people. The People tab in the photo edit dialog shows all faces, so you can name them or report a bad match by pressing the up arrow button.

### When a face was not detected...

There can be several reasons why a face was not detected:

- You may need to wait until indexing is complete, as face recognition will not begin until your library has been scanned.
- Only the primary file in stacks will be searched for faces.
- Faces can be smaller than the minimum size configured.
- Our face detection did not scan the image thoroughly enough.
- Reducing the resolution or quality of generated thumbnails negatively impacts face detection and recognition results, just like when you cannot see properly.
- Contrast plays a major role, so a bright face with gray hair on a gray background may be less obvious to our face detection than it is to you.
- In very rare cases, an actual face may match a blacklist of false positives, like background noise and food that looks like a face.

!!! note

	Recognition compares the similarity of faces. The similarity threshold for a face is reduced when you report a bad match.

### Assign Names to Faces
 
=== "From People:"
   	- Go to People
   	- Go to New
   	- Click on the input field
   	- Start typing a name
	- Press enter
   
   	![Screenshot](https://docs.photoprism.app/user-guide/organize/img/add-name-new-new.jpg)

=== "From Photo Edit dialog:"
   	- Go to People
   	- Go to New
   	- Click on the input field
   	- Start typing a name
   	- Press enter
   
   	![Screenshot](https://docs.photoprism.app/user-guide/organize/img/add-name-edit-new.jpg)

The person you just added will appear under Recognized.

### Hiding People

You can hide a person in the Recognized section by clicking :octicons-x-16: in the upper right corner. Pictures of this person continue to be visible in search results and albums.

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/person-hide-new.jpg)

To see all people including hidden ones, click :material-eye:.

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/person-show-all-new.jpg)

Hidden people can be recovered by clicking :material-eye-off:.

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/person-recover-new.jpg)

### Hiding Faces

You can hide face clusters from the New section, in the same way you hide people from the Recognized section.

### View all Photos of a Person

1. From People:
   - Go to People
   - Go to Recognized
   - Click on the person you want to view
   
   ![Screenshot](https://docs.photoprism.app/user-guide/organize/img/view-person-new.jpg)

2. From Search:
   - Go to People
   - Go to Recognized
   - Click on the person you want to view
   
   ![Screenshot](https://docs.photoprism.app/user-guide/organize/img/view-person-2-new.jpg)

## Labels

PhotoPrism uses labels to classify images. Other tools use the term tags instead of labels. Labels are set automatically when adding new photos. You can manually add new labels or edit/remove the ones that have been created by us.

In Labels, you find all labels of your photos and videos. You can star labels by clicking :octicons-star-fill-24:. Starred labels will be listed first.

PhotoPrism also attaches each generated label to a broader group (or category) of labels. For example, there is a general category 'vehicle' which will include labels such as 'cab', 'catamaran', 'lifeboat' and 'bullet train'. These broad label categories cannot be edited but can be used in a search, in an identical way to all other labels.

You may wish to see these broad label categories in addition to the usual labels in the Labels pages. Clicking the icon in the upper right-hand corner will switch between turning them on :material-arrow-expand-vertical: and off :material-arrow-collapse-vertical:. You can also include these label categories as part of a more complex search filter - the label categories from your photos will appear in the search filter bar as a drop-down selection under the option 'All Categories'.

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/labels-1-light.jpg)

### View all Photos with a Label

1. Go to Labels
2. Click on the label you are interested in

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/labels-2-light.jpg)
![Screenshot](https://docs.photoprism.app/user-guide/organize/img/labels-3-light.jpg)

Alternatively, you can use the search field in Photos/Videos. You search for photos with a special label like this: `label:dog`.

### Add Labels to Photos

1. Go to the photo edit dialog
2. Go to Labels tab
3. Click on the label field in the last row of the label table
4. Enter a label name
5. Click :material-plus: on the right side of this row

![Screenshot]https://docs.photoprism.app/user-guide/organize/img/add-label-light.jpg

### Remove/Delete Labels from Photos

Labels that have been set automatically can be removed. Manually added labels can be deleted.

1. Go to the photo edit dialog
2. Go to Labels tab
3. Click the :material-delete-forever: button of the label you want to remove/delete

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/remove-label-1-light.jpg)

!!! info

	Removed labels have a confidence of 0% and can be activated again at any time by clicking add.

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/remove-label-2-light.jpg)

!!! info

	You can hide Labels in Settings.

### Rename Labels

1. Go to the photo edit dialog of any photo that has the label you want to rename

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/edit-label-1-light.jpg)

2. Go to Labels tab

3. Click on the label name you want to change
4. Change the name and click enter

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/edit-label-2-light.jpg)
![Screenshot](https://docs.photoprism.app/user-guide/organize/img/edit-label-3-light.jpg)

The changes will be applied to all photos with this label after the next indexing.

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/edit-label-4-light.jpg)

!!! info

	Be aware this change applies to all photos that have this label.

### Delete Labels

You can permanently delete a label. No file will get a deleted label set during indexing.

1. Go to Labels
2. Select the label you want to delete
3. Open the context menu
4. Click :material-delete:

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/delete-label-1-light.jpg)

Confirm

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/delete-label-2-light.jpg)

!!! info

	In case you want a deleted label to appear again, you need to add it to one photo and then index all files again.

## Archive

You can move photos and videos you do not want to keep in your collection to Archive. Content that is archived is not deleted but it will not appear in any section apart from Archive.

### Archive Photos

1. Select photos/videos
2. Click context menu
3. Click :material-archive-arrow-down:

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/archive-light.jpg)

### Restore Photos from Archive

1. Go to Archive
2. Select photos/videos
3. Click context menu
4. Click :material-archive-arrow-up:

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/restore-light.jpg)

## Removing Files Permanently

You can permanently delete photo and video files you do not want to keep from your filesystem. Photos and videos must be archived before they can be deleted permanently.

Before you start, make sure the Delete feature is enabled in Settings.

### Delete Selected Files

1. Select the photos and videos you want to delete
2. Go to Archive
3. Click context menu
4. Click :material-delete:
5. Confirm

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/delete-dark.jpg)

### Delete All Archived Photos

1. Go to Archive
2. Click :material-delete-sweep:
3. Click Delete All

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/delete-all-dark.jpg)


##  Hiding Private Photos

### What does private mean?

Some of your photos might be private for personal reasons. Our private functionality provides you with a solution to hide private photos or videos from some sections. This way you can let family and friends browse through your photos without risking that they see photos you do not want them to see.

By default, photos marked as private will not appear in the following sections:

- Search
- Videos
- People
- Favorites
- Places
- Labels
- Autogenerated Albums (Moments, Calendar, States, Folders)
- Shared Albums

Private photos will be displayed in the private section, in user-generated albums, and within the file browser.

In case you want private content to appear everywhere you can configure that in Settings.

### Toggle Private Flag

1. **Using Context Menu**
   - From List View
     1. Go to Search
     2. Select photos/videos
     3. Click context menu
     4. Click :material-lock:

![Screenshot](https://docs.photoprism.app/user-guide/organize/img/private-context-menu-light.jpg)

## Advanced Configuration

### For more information

!!! warning "For Advanced Users Only"

	For complete documentation, including AI and API Documentation, please visit [Offical Documentation](https://docs.photoprism.app/).