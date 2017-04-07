# MS-facesAuth
Some testing
This is pilot testing on how to use the MS Face API to dectect faces and authenticate.
A photo(can have multiple faces) or a live camera shot is authenticated against a group of person that is known
If the any faces in the photo or in the camera shot is known, it is authicated, else it is an unknown person.

This version, for quick and easy way, I just hardcode the test photo path.
For it to work, the folder TestPhotos should be in C drive. e.g C:\TestPhotos
Then start the multifacesAuthentication.sln in Visual Studio
