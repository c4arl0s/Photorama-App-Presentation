# [Go back to iOS Apps](https://github.com/c4arl0s#ios-apps-using-swiftuikit)

In order to update an existing Git submodule execute: (You migh need permissions from Owner)

```console
 git submodule update --remote --merge
```

# [Photorama App](https://github.com/c4arl0s/20WebServices_PhotoramaApp#1-starting-the-photorama-application)

Photorama App make a web service request to get interesting photos from Flickr. 

| Notes                                                                                                                                     | Code                                                                                                                          | Diagrams                                                                                                                      | xproj                                                                                                                         |
|-------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| <img src="https://user-images.githubusercontent.com/24994818/124355087-0ac2fd00-dbd5-11eb-9909-9139df8ebcd7.png" width="250" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/124355190-8fae1680-dbd5-11eb-9ae3-38c702102fb6.png" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/124355305-fe8b6f80-dbd5-11eb-8ff6-15391b0b9e51.png" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/124356742-55e10e00-dbdd-11eb-9faa-03f07ea6a438.gif" width="250"> |

1. [x] [Starting the Photorama Application](https://github.com/c4arl0s/20WebServices_PhotoramaApp#1-starting-the-photorama-application)
2. [x] [Building the URL](https://github.com/c4arl0s/20WebServices_PhotoramaApp#2-building-the-url)
3. [x] [Formatting URLs and requests](https://github.com/c4arl0s/20WebServices_PhotoramaApp#3-formatting-urls-and-requests)
4. [x] [URLComponents](https://github.com/c4arl0s/20WebServices_PhotoramaApp#4-urlcomponents)
5. [x] [Sending the Request](https://github.com/c4arl0s/20WebServices_PhotoramaApp#5-sending-the-request)
6. [x] [URLSession](https://github.com/c4arl0s/20WebServices_PhotoramaApp#6-urlsession)
7. [x] [Modeling the Photo](https://github.com/c4arl0s/20WebServices_PhotoramaApp#7-modeling-the-photo)
8. [x] [JSON Data](https://github.com/c4arl0s/20WebServices_PhotoramaApp#8-json-data)
9. [x] [JSONSerialization](https://github.com/c4arl0s/20WebServices_PhotoramaApp#9-jsonserialization)
10. [x] [Enumerations and associated values](https://github.com/c4arl0s/20WebServices_PhotoramaApp#10-enumerations-and-associated-values)
11. [x] [Parsing JSON data](https://github.com/c4arl0s/20WebServices_PhotoramaApp#11-parsing-json-data)
12. [x] [Downloading and Displaying the Image Data](https://github.com/c4arl0s/20WebServices_PhotoramaApp#12-downloading-and-displaying-the-image-data)
13. [x] [The Main Thread](https://github.com/c4arl0s/20WebServices_PhotoramaApp#13-the-main-thread)
14. [x] [Bronze Challenge: Printing the Response Information](https://github.com/c4arl0s/20WebServices_PhotoramaApp#14-bronze-challenge-printing-the-response-information)
15. [x] [Silver Challenge: Fetch Recent Photos from Flickr](https://github.com/c4arl0s/20WebServices_PhotoramaApp#15-silver-challenge-fetch-recent-photos-from-flickr)
16. [x] [For the More Curious: HTTP](https://github.com/c4arl0s/20WebServices_PhotoramaApp#16-for-the-more-curious-http)

# [CollectionView for PhotoramaApp - Content](https://github.com/c4arl0s/21CollectionView_PhotoramaApp#go-back-to-content)

1. [x] [1. Displaying the Grid](https://github.com/c4arl0s/21CollectionView_PhotoramaApp#1-displaying-the-grid)
2. [x] [2. Collection View Data Source](https://github.com/c4arl0s/21CollectionView_PhotoramaApp#2-collection-view-data-source)
3. [x] [3. Customizing the Layout](https://github.com/c4arl0s/21CollectionView_PhotoramaApp#3-customizing-the-layout)
4. [x] [4. Creating a Custom UICollectionViewCell](https://github.com/c4arl0s/21CollectionView_PhotoramaApp#4-creating-a-custom-uicollectionviewcell)
5. [x] [5. Downloading the Image Data](https://github.com/c4arl0s/21CollectionView_PhotoramaApp#5-downloading-the-image-data)
6. [x] [6. Extensions](https://github.com/c4arl0s/21CollectionView_PhotoramaApp#6-extensions)
7. [x] [7. Image caching](https://github.com/c4arl0s/21CollectionView_PhotoramaApp#7-image-caching)
8. [x] [8. Navigating to a Photo](https://github.com/c4arl0s/21CollectionView_PhotoramaApp#8-navigating-to-a-photo)
9. [ ] [9. Silver Challenge: Updated Item Sizes](https://github.com/c4arl0s/21CollectionView_PhotoramaApp#9-silver-challenge-updated-item-sizes)
10. [ ] [10. Golden Challenge: Creating a Custom Layout](https://github.com/c4arl0s/21CollectionView_PhotoramaApp#10-golden-challenge-creating-a-custom-layout)

|                                                                                                                       |                                                                                                                       |
|-----------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| <img width="695" alt="Image" src="https://github.com/user-attachments/assets/95b1fbfa-1014-4e3f-9b84-c2c5d0afc491" /> | <img width="695" alt="Image" src="https://github.com/user-attachments/assets/ada6e40a-21f3-428a-9a84-003b37742940" /> |
