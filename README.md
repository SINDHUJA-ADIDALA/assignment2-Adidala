# assignment2-Adidala
# Sindhuja Adidala
###### Himachal pradesh

Himachal pradesh is a **northern Indian state** in the Himalayas. It is home to scenic **mountain towns** and resorts such as **Dalhousie**. I like this place because it is well-known for trecking, climbing. 

---


# Directions for travelling from Maryville to Himachal pradesh
1. Book a cab from Maryville to Kansas airport
2. Finish the check-in process through online 
   1. Finish the security check.
   2. Board your Flight.
   3. Waiting for the connecting Flight in Chicago.
3. O'Hare International Airport to Indira Gandhi International Airport
   1. Complete the check-out process in Delhi.
   2. Book a train ticket to Himachal pradesh.
4. Una Himachal Railway Station to Una Comfort Nandini Hotel.

* clothes
* UNO cards
* Pair of Foot Wear
* Snacks
  * choclates
  * cookies

  [image](https://github.com/SINDHUJA-ADIDALA/assignment2-Adidala/blob/main/AboutMe.md)

  ---

  # Table Creation

  The above table recommends some of my best food and drinks I experienced till now

  |          Food                        |        Drink                | Price   |
  |          ----                        |        -----                | -----   |
  |       Chicken Sandwich               |       Coke                  | $8      |
  |       Chicken cheese pizza           |      Vanila Milkshake       | $10     |
  |       Chicken Nuggets                |      Caramel Frapuchino     | $12     |
  |       Chicken Taco                   |      Choclate Almond Milk   | $ 13    |


# Quotes by greatest people

> "Spread love everywhere you go. Let no one ever come to you without leaving happier"- by ***Mother Teresa*** <br>
> "The best and most beautiful things in the world cannot be seen or even touched — they must be felt with the heart"- by ***Helen Keller***


# Algorithm on Polygons
 
>  This course focuses on the recovery of the 3D structure of a scene from its 2D images. In particular, we are interested in the 3D reconstruction of a rigid scene from images taken by a stationary camera (same viewpoint). This problem is interesting as we want the multiple images of the scene to capture complementary information despite the fact that the scene is rigid and the camera is fixed. To this end, we explore several ways of capturing images where each image provides additional information about the scene.



Source link for the definition - <https://www.coursera.org./learn/3d-reconstruction >

---

 int signed_area_parallelogram(point2d p1, point2d p2, point2d p3) {
    return cross(p2 - p1, p3 - p2);
}

double triangle_area(point2d p1, point2d p2, point2d p3) {
    return abs(signed_area_parallelogram(p1, p2, p3)) / 2.0;
}

bool clockwise(point2d p1, point2d p2, point2d p3) {
    return signed_area_parallelogram(p1, p2, p3) < 0;
}

bool counter_clockwise(point2d p1, point2d p2, point2d p3) {
    return signed_area_parallelogram(p1, p2, p3) > 0;
}

---

Source link for code - <https://cp-algorithms.com/geometry/oriented-triangle-area.html>


