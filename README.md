# Project1
UIKit based project displaying images

Following are the highlights of this small basic project,
1. UITableViewController and UIViewController are subclassed
2. Methods from the conforming protocol UITableViewDataSource is used to create and manage the table cells.
3. UIImageView class is utilised for managing the various operations involved with the image files i.e searching the image in the main bundle and
displaying.
4. @IBOutlet attribute is for connecting an element in the storyboard with code
5. UINavigationViewController is also embedded to enable navigation between multiple view controllers.
6. Extension is written for the viewController to include all those codes that are part of the conforming protocol

The basic functionality of this application is - there is a resource path provided for lookup. If the path contains any resources with the .jpg suffix,
the for-loop will assign all those values within an array of string. Those elements that are inside the array are then passed to the detailViewController
called from inside the didSelectRowAt method of the protocol, where the image is displayed.
