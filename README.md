# MS-facesAuth
Reference : https://www.microsoft.com/cognitive-services/en-us/face-api/documentation/face-api-how-to-topics/howtoidentifyfacesinimage

Some testing.
This is a pilot testing on how to use the MS Face API to dectect faces and authenticate.
A photo(can have multiple faces) or a live camera shot is authenticated against a group of persons that are known.
If any faces in the photo upload or in the camera shot is known, it is authicated to known, else it is an unknown person.

This version, for quick and easy way, I just hardcoded the test photo path.
For it to work, the folder TestPhotos should be in C drive. e.g C:\TestPhotos
Then start the multifacesAuthentication.sln in Visual Studio
