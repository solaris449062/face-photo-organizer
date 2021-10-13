# **Face recognition photo organizer**

This app should make picture search easy by identifying who is in the picture.

1. User will upload different pictures. For face recognition, there needs to be enough number of pictures where a person's face features are clearly visible.
2. The app will recognize and identify different people in the picture using face recognition using deep learning.

[^face-recognition-repository]: [Python library: face_recognition ](https://github.com/ageitgey/face_recognition)
[^dlib]: [dlib](https://github.com/ageitgey/face_recognition)

3. The user will then name the identified people.
4. After the identification is complete, the app organizes the photos by people. 
5. The user can search for people. The query can be for a single person "Barack Obama", or multiple people "Barack Obama" and "Michelle Obama". One of the primary functions for the app is to return the user the pictures where multiple specified people are together in a single photo.

Stretch goals:

1. Sort using image metadata

2. If location is available in the metadata, use Google map to display it.

2. Sort using background.
   - nature
   - indoor
   - etc.

3. linking to image folder in cloud services (not having to upload)

4. make it work even with wearing mask

### **Technology to be used in the app**

1. Deep learning for face recognition[^face-recognition-repository][^dlib]
2. React for the frontend
3. Rails for the backend
4. Authentication for the different users

### **ERD**

![ERD](https://github.com/solaris449062/face-photo-organizer/blob/main/readme-img/ERD.png)

<!-- ```mermaid
erDiagram
    User ||--o{ Photo : ""
    User ||--o{ People : ""
    Photo }o--|{ People : ""
``` -->



### Wireframes

![Main](https://github.com/solaris449062/face-photo-organizer/blob/main/readme-img/main.png)

![Find](https://github.com/solaris449062/face-photo-organizer/blob/main/readme-img/find.png)

![Search](https://github.com/solaris449062/face-photo-organizer/blob/main/readme-img/search.png)


