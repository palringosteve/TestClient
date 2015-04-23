TestClient
==========

- Install and integrate CocoaPods.
- Install AFNetworking 2.5.3 as a CocoaPod.
- Use AFNetworking and the URLs generated by the [SBFlickrHelper](https://github.com/palringosteve/TestClient/blob/master/FlickrClient/SBFlickrHelper.h) class to retrieve a list of photos from Flickr.
- Use storyboard(s) and segue(s) to display and navigate between view controller.
- Display the small versions of these photos in a collection view in [SBPhotoListViewController](https://github.com/palringosteve/TestClient/blob/master/FlickrClient/SBPhotoListViewController.h).
- Tapping on a photo in the collection view should push a [SBPhotoDetailViewController](https://github.com/palringosteve/TestClient/blob/master/FlickrClient/SBPhotoDetailViewController.h) onto the navigation stack.
- The [SBPhotoDetailViewController](https://github.com/palringosteve/TestClient/blob/master/FlickrClient/SBPhotoDetailViewController.h) should display a larger version of the photo along with a map indicating the geo-location of where the photo was taken and other information as defined in the header file.

__Bonus points__
- Use Auto Layout.
- Display more information about the photo in the [SBPhotoDetailViewController](https://github.com/palringosteve/TestClient/blob/master/FlickrClient/SBPhotoDetailViewController.h).
