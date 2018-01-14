# banners.css
![Screenshot](screenshot.png)
banners.css is a simple CSS preset to allow easy creation of simulated [FRC](http://firstinspires.org/robotics/frc) blue banners (typically presented to teams upon receiving a competition award).

It is most famously used on [The Blue Alliance](https://thebluealliance.com), to show awards a team has won.

## Instructions
This framework allows for three different types of banner markup:

### Row
To define a group of banners:  
1. Create a `<ul>` with the class of `banners`. Each `<li>` in the list will be turned into a banner.  
2. OPTIONAL: Insert an `<img>` at the starting of each `<li>` with the `src` pointing to the `first.svg` file  included in this repository. This will put a FIRST logo on the banner. This can be done for all three methods of declaring a banner.  
3. Fill the rest of each `<li>` with the name of the award. Well, technically, you can put any content you want in it. But the name of the award is probably best.

### Individual banner
Repeat the above process, except instead of defining a `<ul>` with `<li>`s as children, define one `<div>` with the class of `banner`. Treat this like you would a `<li>` in the process above.

### Page-wide
Repeat the first process exactly, however with one extra step: enclose the `<ul>` with a `<div>` with the class `banner-parent`. This will cause the row of banners to expand to fill the whole width of the screen, and any extra banners will be visible by scrolling to the side.

## Examples
* See `example.html`
* [Team](http://www.thebluealliance.com/team/254/2014) and [Team History](http://www.thebluealliance.com/team/254/history) pages on The Blue Alliance (heavily modified, but based off this framework)
* [Team 1418's website](http://1418.team)
* [Team 1257's awards page](http://team1257.org/#awards)
* [Team 3492's about page](http://parts3492.org/about/)

If you use this framework on your own project, feel free to open a pull request to add it to this list!

## Author
This framework was created by [Erik Boesen](https://github.com/ErikBoesen), originally for [Team 1418's website](http://1418.team).

## License
This software is protected under the CC-0 license. Do anything you want with it. I'd love if you gave me credit, but you don't have to if you really don't want to.
