TestClient
==========

__Basic Idea__
This is a simple iOS 8 iPhone app that shows photos and where they where taken.

__Required__
- Use the URLs generated by the [SBFlickrHelper](https://github.com/palringosteve/TestClient/blob/master/FlickrClient/SBFlickrHelper.h) class to retrieve a list of photos from Flickr.
- Use storyboard(s) and segue(s) to display and navigate between view controllers.
- Display the small versions of these photos in a collection view in [SBPhotoListViewController](https://github.com/palringosteve/TestClient/blob/master/FlickrClient/SBPhotoListViewController.h).
- Tapping on a photo in the collection view should push a [SBPhotoDetailViewController](https://github.com/palringosteve/TestClient/blob/master/FlickrClient/SBPhotoDetailViewController.h) onto the navigation stack.
- The [SBPhotoDetailViewController](https://github.com/palringosteve/TestClient/blob/master/FlickrClient/SBPhotoDetailViewController.h) should display a larger version of the photo along with a map indicating the geo-location of where the photo was taken and other information as defined in the header file.
- You can use any 3rd party frameworks as long as you can justify your choices.

__Bonus points__
- Use Auto Layout and Size Classes.
- Display more information about the photo in the [SBPhotoDetailViewController](https://github.com/palringosteve/TestClient/blob/master/FlickrClient/SBPhotoDetailViewController.h).
