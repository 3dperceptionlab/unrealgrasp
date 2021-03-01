[videocover0]: ./img/unrealgrasp_cover0.png
[videocover1]: ./img/unrealgrasp_cover1.png

# UnrealGrasp

[![videocover0]](https://www.youtube.com/watch?v=65gdFdwsTVg)

Interaction in virtual reality (VR) environments is essential to achieve a pleasant and immersive experience. Most of the currently existing VR applications, lack of a robust object grasping and manipulation system, which is the cornerstone of any interaction system. Therefore, we propose a realistic, ﬂexible and robust grasping system that enables rich and real-time interactions in virtual environments. It is visually realistic because it is completely user-controlled, ﬂexible because it can be used for diﬀerent hand conﬁgurations, and robust because it allows the manipulation of objects regardless their geometry, i.e. hand is automatically ﬁtted to the object shape. In order to validate our proposal, an exhaustive qualitative and quantitative performance analysis has been carried out. On the one hand, qualitative evaluation was used in the assessment of abstract aspects such as: hands movement realism, interaction realism and motor control. On the other hand, for the quantitative evaluation a novel error metric has been proposed to visually analyze the performed grips. This metric is based on the computation of the distance from the ﬁnger phalanges to nearest contact point on the object surface. These contact points can be used with application purposes mainly in the ﬁeld of robotics. As a conclusion, system evaluation reports a similar performance between users with previous experience in virtual reality applications and inexperienced users, referring to a steep learning curve.



In the following video we can observe the quantitative evaluation where we smoothly interact with objects from the YCB dataset:
[![videocover1]](https://youtu.be/4sPhLbHpywM)


## Important note

Because of copyright, the realistic scenario and hands are not available in the uploaded projects. In provided versions, grasping system works with UE4 mannequin in a basic scenario (such as we can see in the second video performing the quantitative evaluation).

## Available versions

Project is available for different Unreal Engine versions such as: 4.19, 4.20 and 4.21. A git branch was created for each version, so please select the corresponding branch to access the desired version. Note that master branch is experimental and some plugins are requierd to make the project work. 

## Paper

Sergiu Oprea, Pablo Martinez-Gonzalez, Alberto Garcia-Garcia, John Alejandro Castro-Vargas, Sergio Orts-Escolano, and Jose Garcia-Rodriguez [A visually realistic grasping system for object manipulation and interaction in virtual reality environments](https://www.sciencedirect.com/science/article/pii/S0097849319301098)

Work submitted to Computer and Graphics journal (El Sevier).

If you use UnrealROX, please cite:

```
@article{Oprea2019,
title = "A visually realistic grasping system for object manipulation and interaction in virtual reality environments",
journal = "Computers & Graphics",
volume = "83",
pages = "77 - 86",
year = "2019",
issn = "0097-8493",
doi = "https://doi.org/10.1016/j.cag.2019.07.003",
url = "http://www.sciencedirect.com/science/article/pii/S0097849319301098",
author = "Sergiu Oprea and Pablo Martinez-Gonzalez and Alberto Garcia-Garcia and John A. Castro-Vargas and Sergio Orts-Escolano and Jose Garcia-Rodriguez",
keywords = "Human-computer interaction, Virtual reality, User studies",
abstract = "Interaction in virtual reality (VR) environments (e.g. grasping and manipulating virtual objects) is essential to ensure a pleasant and immersive experience. In this work, we propose a visually realistic, flexible and robust grasping system that enables real-time interactions in virtual environments. Resulting grasps are visually realistic because hand is automatically fitted to the object shape from a position and orientation determined by the user using the VR handheld controllers (e.g. Oculus Touch motion controllers). Our approach is flexible because it can be adapted to different hand meshes (e.g. human or robotic hands) and it is also easily customizable. Moreover, it enables interaction with different objects regardless their geometries. In order to validate our proposal, an exhaustive qualitative and quantitative performance analysis has been carried out. On one hand, qualitative evaluation was used in the assessment of abstract aspects, such as motor control, finger movement realism, and interaction realism. On the other hand, for the quantitative evaluation a novel metric has been proposed to visually analyze the performed grips. Performance analysis results indicate that previous experience with our grasping system is not a prerequisite for an enjoyable, natural and intuitive VR interaction experience."
}
```
## License

This code is released under the GPL-3.0 License.

## Contact / Authors

Any criticism and improvements are welcome using the issue system from this repository. For other questions, contact the corresponding authors:

- Sergiu Oprea ([soprea@dtic.ua.es](mailto:soprea@dtic.ua.es))
- Pablo Martinez-Gonzalez ([pmartinez@dtic.ua.es](mailto:pmartinez@dtic.ua.es))
- Alberto Garcia-Garcia ([agarcia@dtic.ua.es](mailto:agarcia@dtic.ua.es))
- John A. Castro-Vargas ([jacastro@dtic.ua.es](mailto:jacastro@dtic.ua.es))
- Sergio Orts-Escolano ([sorts@ua.es](mailto:sorts@ua.es))
- Jose Garcia-Rodriguez ([jgarcia@dtic.ua.es](mailto:jgarcia@dtic.ua.es))
