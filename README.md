# Max for Live
Max For Live devices and other Max stuff
<br>
<br>

### Velocity Mapper

<img src="https://raw.githubusercontent.com/cvolm/max/master/Images/velocity-mapper.png" width="518">

This device lets you play around with velocity data and map it to different destinations. The final output data can be mapped to aftertouch, pitchbend and up to four different CC types at the same time.

Features:
* Amount and Drive to control intensity
* Low and High to set minimum and maximum values
* Delay data by note values from 1/64 to 1/2
* Invert intensity (highest value becomes lowest value)
* Note Off to also trigger data output on note off for nice effects
* Input and output monitoring
<br>
<br>

### Perfourmer Control

<img src="https://github.com/cvolm/max/blob/master/Images/perfourmer-control.png" width="331">

One thing that always bugs me about the Vermona Perfourmer Mk2 is that you can't control filter cutoff with velocity. This device solves that and adds velocity control to the filter by using aftertouch messages. I also added some extras to modify the velocity input data:
* Amount and Drive to control how intense velocity impacts the filter cutoff
* Low and High to set minimum and maximum values
* Input and output monitoring

I also added a dial for PWM amount, as that's also missing on the Perfourmer.

You can also use the Velocity Mapper device (or any other velocity mapper that lets you map to aftertouch) to control the filter cutoff on the Perfourmer.
