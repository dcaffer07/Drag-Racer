# Drag Racer - Engineering 2 (Dom & Zac)


## Table of Contents 
* [Planning Stage](https://github.com/dcaffer07/Drag-Racer/blob/main/README.md#planning---detailed-description-with-images) 
* [Materials Used](https://github.com/dcaffer07/Drag-Racer/blob/main/README.md#materials-used)
* [CAD Model](https://github.com/dcaffer07/Drag-Racer/blob/main/README.md#cad-model---link-and-images)
* [Wiring Diagram](https://github.com/dcaffer07/Drag-Racer/blob/main/README.md#wiring-diagram) 
* [Arduino Code](https://github.com/dcaffer07/Drag-Racer/blob/main/README.md#arduino-code)
* [Final Design/Product](https://github.com/dcaffer07/Drag-Racer/blob/main/README.md#final-designproduct)
* [Reflection](https://github.com/dcaffer07/Drag-Racer/blob/main/README.md#reflection-3)


## Planning - detailed description with images
#### Purpose & Expectations
> To work diligently in order to create a product that improves and expands our overall knowledge of how basic engineering operates.  We are expected to work professionally, using our time and resources wisely.  We are expected to work with our partners efficiently to create an object that operates under the parameters provided. With this we will create a device that incorporates all of the aspects of engineering we have learned about to scare and startle those who aren’t scared and startled enough in an effort to make the world a less scared-and-startle-free space.

#### Description (establishing the foundation)
> Design, Build, and Program a Drag Race Car to safely and quickly travel a length of 10ft and across the finish line in the fastest time.  Have a photo interrupter put at the most front portion of your car. Allow adjustment of your photointerrupter to have a height between 80mm and 100mm. Push Button must be included. Work in a partnership and get to work!

#### Planning Document
[Here is the planning doc that was created pre-creation](https://docs.google.com/document/d/14ydlslu0jilWMhaa84WuWhr467ZRmgDgo2GTIVmntT8/edit#heading=h.ukbi0a75zb46)

#### Initial Sketch
<img src="https://github.com/dcaffer07/Drag-Racer/blob/main/dragrace.jpg?raw=true" alt="wiring2" style="width:195px;"> <img src="https://assets.whichcar.com.au/image/upload/s--Ng54hpmk--/ar_2.304921968787515,c_fill,f_auto,q_auto:good/v1/archive/streetmachine/2015/08/14/42751/WEB-Cars-4-nw.jpg?raw=true" alt="wiring2" style="width:600px;">

#### Reflection of Planning (done post project)
> All in all I think that our planning went well. In all honesty I wish that we had looked more closely into the logic behind things, but as I said, the project turned out similarly to as we expected.  However with that being said, here are some things that I wish I had known or looked more closely into before the assignment...
>- We did not really consider the buttons' role in the project. Come run time, we had no way to access the button while still having the frame on top of the car.
>- I would have liked to have left more space in most aspects... This was the case in the wheel situation, as the wheels initially didn't fit so we had to sand the base down.  This was also the case in the gears as they were more thought than anticipated.  
>- I would have liked to pay more attention to the timeline aspect of planning.  I feel like we were nonchalaunt in the beginning, and crunching for time toward the end.  But we got it done.
>- Complete engineering notebook as you go along.  I have said this before and I say it again, it is a mistake that we have made and I consistently see my classmates make... do notebook!
>
> As stated, our planning was not perfect, but it was sufficient and seemed to work well enough.  

____
## Materials Used
>- Acrylic (base of box and windows)
>- 3d printer (gears, gear shaft, outer frame, motor holders)
>- Standard button (for initialization)
>- Wires 
>- T-Slot Photo Interrupter (To send racer)
>- H-Bridge (signals servo to stop)
>- TT Motor X 2
>- Panel Mount LED
>- Panel Mount Switch
>- Arduino...  prototyping shield... mini breadboard
>- Battery pack (6 x AA)
>- Screws/nuts/washers... assorted
_____
## CAD Model - Link and Images
#### Description
> While planning, we liked the idea of an open concept car.  This was the case because although we wanted an outer shell in order for the object to look like a car, we liked the idea of being able to see the insides of the device.  This design consists of a base, which holds all of the necessary electronics along with the gears and shaft mechanism, while having an outer shell frame made of 3D printed material, covered in clear acrylic.  These acrylic "windows" allow for the LED and Switch to be attached in the back with the photointerrupter in the front window.  With this design, we should be able to combine functionality with our own sense of style, while utilizing the wide array of materials at our disposal.

#### Evidence
[The Drag Racer in OnShape](https://cvilleschools.onshape.com/documents/e8806f96e774d3def5e33240/w/76c1360de77130e99abc977a/e/2fdb9a68a300250b81b92fe9)
#### Image
<img src="https://github.com/dcaffer07/Drag-Racer/blob/main/Full%20car.png?raw=true" alt="wiring2" style="width:270px;"><img src="https://github.com/dcaffer07/Drag-Racer/blob/main/gear.png?raw=true" alt="wiring2" style="width:150px;"><img src="https://github.com/dcaffer07/Drag-Racer/blob/main/top%20view.png?raw=true" alt="wiring2" style="width:230px;"><img src="https://github.com/dcaffer07/Drag-Racer/blob/main/Gear%20Shaft.png?raw=true" alt="wiring2" style="width:230px;">


#### Reflection
> All in all the construction and printing itself was relatively easy despite a few hiccups, however after going through it, here are a few takeaways from my experience creating this...
>- Prevent the use of unnecessary material... try to be mindful of what is being used, especially when working with 3D material.  We were initially planning on a completely 3D printed object, however that would not have been costly and efficient.
>- Buy battery packs facing outside the object for easy access to battery switches.
>- Always leave yourself more room than anticipated. The wheels fit in the CAD design but not in real life which was frustrating.
>- Attach accordingly and in order and make sure that you  have a full understanding of what needs to happen... we did not largely consider the button which is very important.
>All in all it was a fun build and I am pretty super happy with the way it came out.
___
## Wiring Diagram
#### Descriptions
> With all of the different aspects, we expected this wiring to be difficult... and it lived up to its expectations.  The goal is to initiate the program by pressing a standard button... which then was triggered by a photointerrupter, causing the car to move forward 10 feet to the finish line where it would have to stop within a foot behind the finish line. In addition to these aspects, an LED and Switch were required to turn on the device which was powered by 6 AA batteries stationed on a standard battery pack.  The cooperation of these different facets was dependent on the use of an H-Bridge, as the functionality of all of these things were for the purpose of the TT Motors which turned the gears.  We were able to do this with all of the equipment present in the lab, and after some trial and error, it would finally work in sync with the code.

#### Image/ Diagram ([Wiring Diagram in TinkerCad](https://github.com/dcaffer07/Drag-Racer/blob/main/README.md))
<img src="Dragracerwiring.png" alt="Dragracerwiring"  style="width:500px;">

#### Reflection
> Despite some troubles involving our H-Bridge (not functioning correctly which caused the device not to work), and some problems with exposed wires, we were able to diligently and effectively establish wiring that worked effectively. However, like anything else, here are some takeaways from this aspect of the projects as well as things to keep in mind in the future...
> - When cutting wires, make sure that you do not leave too much exposed wire on the ends.  This can cause confusing shorts that vary depending on movement.
> - When struggling to make the code function without reason as to why, be sure to check the larger components for functionality such as the H-Bridge which happened to be the tube in this particular case.
> - When possible, use resistors.  It will cause the elimination of random influxes of energy that can cause things to function haphazardly.
> - When struggling to move forward with the wiring, try to take things step by step, and focus on more individualized aspects rather than the entire object.
>
>Despite having not known these things beforehand, we were able to make our racer work effectively with the help of Mr. Garcia and Mr. H.
___
## Arduino code
#### Description
> The goal of this code was to use photointeruots and a oushbutton to innitialize the turning of TT Motors 10 feet to the finish line, where the dice would then stop within a foot of the finish line. We would do this using an H-Bridge, which meant the integration of the Ain1/2, Bin1/2, and other more standard pins with a value to give them a resting state which could be built upon or varies later in the program.  From there we established the functions forward and break which would be dependent on the state of the photointerrupter and buttons.  These functions would create the needed combinations for TT motors to operate, causing the device to either move or stop.  This code was difficult, however it proved to work effectively and in the manner that we had hoped.  


#### Evidence ([CODE on Arduino.cc](https://create.arduino.cc/editor/zsiller38/93f3e2bb-a89a-4506-b8e6-ee0f0d1aa9e8/preview))

```C++

// Dominick Cafferillo & Zachary Siller
// Drag Racer

int Ain1 = 9;
int Ain2 = 10;
int Bin1 = 5;
int Bin2 = 6;
int photoPin = 2;
int buttonPin = 11;
int state = LOW;
int buttonState = LOW;
int var = LOW;

int RUNTIME = 3000; //changes how long motor is on for
void brake() {
  digitalWrite(Ain1, LOW);  //turns motors off
  digitalWrite(Ain2, LOW);
  digitalWrite(Bin1, LOW);  //turns motors off
  digitalWrite(Bin2, LOW);

}
void forward() {
  analogWrite(Ain1, 255);  //turns motors on
  digitalWrite(Ain2, HIGH);
  analogWrite(Bin1, 255);  //turns motors on
  digitalWrite(Bin2, HIGH);
}


void setup() {
  pinMode(photoPin, INPUT_PULLUP);  //Pullup for photointerrupter
  pinMode(buttonPin, INPUT_PULLUP);
  attachInterrupt(digitalPinToInterrupt(photoPin), blink, CHANGE);  //Interrupt function to trigger photointerrupter without delay, so car starts as soon as possible
  Serial.begin(9600);
  pinMode(Ain1, OUTPUT);
  pinMode(Ain2, OUTPUT);
  pinMode(Bin1, OUTPUT);
  pinMode(Bin2, OUTPUT);

}


void blink() {
  state = !state; //changes state when photointerrupter is changed
}

void loop() {

  Serial.println(var);
  if (state == HIGH) {  //When photo changes
    Serial.println(buttonState);
    buttonState = digitalRead(buttonPin); //Check if button is also pressed since photo is HIGH
    if (buttonState == HIGH) {  //If button is also pressed
      var = HIGH; //Changes Var to signal photo and button both High

    }
    Serial.println(var);
  }

  if (state == LOW && var == HIGH) {  //if button state is high and photointerrupter state is high, but the photointerrupter state changes back to low
    forward(); start motors
    delay(RUNTIME);   //Go for a certain amount of time
    brake(); stop motors
    var = LOW;  //Reset var to low
  }
}

```


#### Reflection
> We expected the code to be very challenging because of the many components we had but it was achievable and it functions.  It required the use of all prior coding knowledge, however as always, some takeaways...    
>- Always double check your pin holes to make sure they are in the correct spot. You can waste a lot of time trying to find an issue with your code when it might be a problem with your wiring.
>- Check the necessary states of the code to make the motors function in the proper manner. 
>- Think about code rationally and verbally before creating it to understand the different aspects.
>- While looking at others' code can be helpful, it wasn't in this case, by doing this im=ndependently it was much more effective. 
>
> As stated, the code was challenging, however it has made us better engineers as a whole.
____
## Final Design/Product
#### Reactions:
> Zac
> - I like projects.
> 
> Dom
> - All in all, I am happy with how our project turned out. It was definitely challenging, however we were able to overcome some tough mishaps and calculations, which I could not be more happy with.  In all honesty I think that we may have been slightly rushed, however I do not believe that we were the only ones and we were still able to make most of our designs. This project has challenged me as a whole, and I look forward to more like it in the future.

#### Final Project Images
<img src="https://github.com/dcaffer07/Drag-Racer/blob/main/back%20final.jpg?raw=true" alt="wiring2" style="width:215px;"> <img src="https://github.com/dcaffer07/Drag-Racer/blob/main/top%20final.jpg?raw=true" alt="wiring2" style="width:300px;"> <img src="https://github.com/dcaffer07/Drag-Racer/blob/main/side%20final.jpg?raw=true" alt="wiring2" style="width:333px;"><img src="https://github.com/dcaffer07/Drag-Racer/blob/main/DR%20Vid.gif?raw=true" alt="wiring2" style="width:100px;">
______
## Reflection
#### Problems, Miscalculations, and Corrections
##### Design/ Initial Stage Issues
###### *Time Management and Milestones*
+ Problem: At the early stages of this project, like most, we probably did  ot work as diligently as possible, while forgetting to follow our milestones intensely.
- Solution: This problem was simply solved by working very long and hard at the end, which meant coming to the lab during other classes in the final week.
###### *Minimizing Material*
+ Problem: We were originally struggling to find a way to make the boc interesting and original without using an abundance of 3D printed material.
+ Solution: Zac came up with a frame design which involved a 3D printed skeleton with pieces of acrylic lining it.
##### CAD Issues
###### *Frame Design*
+ Problem: making the frame was a pain, as several issues came up with size, plane, and material constraints.
+ Solution: We had to create the frame in separate pieces that would be attracted later in the build.
###### *Meeting Size Requirements*
+ Problem: When we weren't dealing with the project being too small, we were dealing with it being too big.  The size requirements gave us unnecessary struggle. 
+ Solution: This problem was solved b y making several adjustments to the design until it met the criteria.
##### Code/Wiring Issues
###### *H-Bridge* 
+ Problem: Our H-Bridge was not functional which caused the entire project to be non-functional.
+ Solution: Simple, we got a new H-Bridge.
###### *Exposed Wire*
+ Problem: When cutting wires, we left too much uncovered wire at the end, which led to shorts throughout the device.
+ Solution: Again, a simple fix, switch the wires out for more trustworthy lines.
##### Build Issues
###### *Shaft Length*
+ Problem: Although they fit in the CAD design, come time to build, the shaft that held the wheels and gears were not long enough to clear the base of the car. 
+ Solution: We had to file down the edges of the base where the wheels would be to allow for more space.
###### *Button Access*
+ Problem: We never really anticipated the fact that we would need to access a button, which did not cooperate fully with our design.
+ Solution: But allowing access to the arduino, we were able to use the button effectively and in the correct manner.


#### Final Thoughts
> The process of making the drag race was extremely frustrating. We ran into several issues primarily with our code that took several class periods to fix.
>- When wiring up the arduino some of our wires were long so we created several short circuits that prevented the arduino functioning as intended. However this issue was fixed by replacing the more problematic wires and double checking how our arduino was mounted to our base. 
>- A second issue we had was with our rear axle we did not make it long enough and as a result the wheels would scrape along the sides of our base. This was fixed by reducing the width of the base where the rear axle was located, but doing this meant we could no longer attach our side panels because they would interfere with our wheels. This was disappointing but the lesson learned was to make a larger axel so we would have more wiggle room when mounting our wheels. 
>- Time management was the final issue with our project. We could have been more focused during some class periods so we would not have to stress over completing a large part of the project in the last few days. 
> Overall I really like the design of our car, and it looks really cool. The build experience and the coding however was not fun due to the issues mentioned above. The project was still fun but I enjoyed the experience of the Jack in the box more.

[Back to the Top](https://github.com/dcaffer07/Drag-Racer/blob/main/README.md#drag-racer---engineering-2-dom--zac)
