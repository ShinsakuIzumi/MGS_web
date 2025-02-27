# Mass Game Simulator: Web-Based Version
This is a web-based simulator of *multi-agent mass games*.

## Multi-Agent Mass Games [1,2]
In multi-agent mass games, agents achieve formations displaying *grayscale images* by distributed control. One potential application of mass games is entertainment, where we can observe the interesting behavior of agents to represent objects and situations depicted in images.

![massgame2](https://user-images.githubusercontent.com/76646096/103174110-d0357c00-48a2-11eb-9a4c-739cc3fa57c7.jpg)

## Mass Game Simulator [3]
The mass game simulator (MGS) was developed to overcome the difficulty in implementing the algorithm for simulating mass games. With the MGS, we can simulate mass games only through mouse and keyboard operations without the need for expert knowledge or programming effort. See [the repository](https://github.com/ShinsakuIzumi/Mass_Game_Simulator) for details.
Meanwhile, the MGS requires MATLAB, which entails cost and effort for its purchase and installation. This limits the number of potential users of the MGS.

## Features of Web-Based Version
To address the above problem, a web-based version of the MGS with the following features has been developed:
- The simulator runs on web browsers (e.g., Microsoft Edge and Google Chrome) and thus can be used as long as an internet connection is available. 
- The users of the simulator do not need to consult an external user manual or prepare a reference image. 
- The choices for the simulation settings (e.g., the number of agents) are more straightforward, reducing the complexity of the simulator's operation.

![Image](https://github.com/user-attachments/assets/899a0dd1-e53f-46d0-a76d-a03acfabc92f)

## Usage
The simulator is available on [the website](https://www.sceng.kochi-tech.ac.jp/izumi/MGS/MGS_web.html), and a user manual is at the bottom of the site.

## License
This software, *except for the csv files in the "images" folder*, is released under the MIT License. The images generated from the csv files are sourced from standard images (see, e.g., [the website](http://www.ess.ic.kanagawa-it.ac.jp/app_images_j.html)) in the image processing community for research purposes, and the author does not claim any rights to the images. If you use these files, please note this point.

## References
[1] S. Azuma, S. Izumi, and T. Sugie: Halftone Mass Games by Fixed Number of Mobile Robots, *Transactions of the Institute of Systems, Control and Information Engineers*, Vol. 25, No. 4, pp. 94-100 (2012) (in Japanese)

[2] S. Izumi, S. Azuma, and T. Sugie: Distributed Hybrid Controllers for Multi-Agent Mass Games by a Variable Number of Player Agents, *Asian Journal of Control*, Vol. 17, No. 3, pp. 762-774 (2015)

[3] S. Izumi, Y. Shiomoto, and X. Xin: Mass Game Simulator: An Entertainment Application of Multiagent Control, *IEEE Access*, Vol. 9, pp. 4129-4140 (2021) [Open Access](https://ieeexplore.ieee.org/document/9311128)
