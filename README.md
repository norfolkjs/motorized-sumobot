# :car: Motorized Sumobot :blue_car:

This is the Norfolk.js motorized version of [Pawel's Sumobot-jr](https://github.com/makenai/sumobot-jr/blob/master/README.md) design that we put together for [NodeBots Day 2016](https://github.com/nodebots/nodebotsday). The main change was to the laser-cut side pieces to support gear motors (inspired by [Markus's sumobot](https://github.com/ghtomcat/sumobot)) and the laser-cut wheels have been replaced by rubber wheels. To make this beginner-friendly, we use a motor shield for wiring the motors to the arduino. However, the bot chassis design can support other motor drivers and wiring strategies.

Want to make your own motorized sumobot? Here is the [parts list](https://github.com/norfolkjs/motorized-sumobot/blob/master/parts_list.md).

We also have [printable instructions](https://github.com/norfolkjs/motorized-sumobot/blob/master/assembly-instructions.pdf) and an instructional video! (thanks [Trisha](https://github.com/aureately) and [Paul](https://github.com/paulchinjr))

[![Instructional Video](https://img.youtube.com/vi/xHns3qxffYM/0.jpg)](https://www.youtube.com/watch?v=xHns3qxffYM)

## Getting Started

### Install Dependencies

* [Git](https://git-scm.com/download)

* [Node 6](https://nodejs.org/en/)

If you're using Windows, you'll also need to install the [Arduino IDE](https://www.arduino.cc/en/Main/Software)

```
  git clone https://github.com/norfolkjs/motorized-sumobot.git
  cd motorized-sumobot
  npm i
  npm i -g firmata-party
```

### Controlling Your Bot

* Plug your Arduino into your computer's USB port
* Flash your Arduino with the Firmata sketch:
  `firmata-party uno --debug`
* Start the code that controls your bot!
  `npm start`

## Looking for More?

* [The Original Pawel-Bot Sumobot-jr](http://www.sumobotkit.com)
* [ETA's Node.js Soccerbot mBots](https://github.com/EmergingTechnologyAdvisors/mbot-soccer)

## NodeBots Day Norfolk
* [NodeBots Day Celebration](http://www.norfolkjs.org/nodebots/index.html)

## License

[Creative Commons - Attribution - ShareAlike 3.0](http://creativecommons.org/licenses/by-sa/3.0/)

You are free to:

+ to Share — to copy, distribute and transmit the work, and
+ to Remix — to adapt the work
+ Under the following conditions:
    + Attribution — You must attribute the work in the manner specified by the author or licensor (but not in any way that suggests that they endorse you or your use of the work)
    + Share Alike — If you alter, transform, or build upon this work, you may distribute the resulting work only under the same, similar or a compatible license.

With the understanding that:

+ Waiver — Any of the above conditions can be waived if you get permission from the copyright holder.
+ Other Rights — In no way are any of the following rights affected by the license:
    + your fair dealing or fair use rights;
    + the author's moral rights; and
    + rights other persons may have either in the work itself or in how the work is used, such as publicity or privacy rights.

## Special Thanks and Credits

* :sparkles: [@makenai](https://github.com/makenai) :sparkles:
* :sparkles: [757 Makerspace](www.757makerspace.com) and [@beauturner](https://github.com/beauturner) :sparkles:
* :sparkles: [@twtomcat](https://github.com/ghtomcat) :sparkles:
* :sparkles: [@aureately](https://github.com/aureately) :sparkles:
