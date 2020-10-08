# Chapter - 1

## Computer Graphics

- Computer Graphics(CG), is the pictures or graphics objects presented at the screen of the computer.
- They are presented as a collection of discrete elements called `Pixels` (Picture elements).
- A `Pixel` is the smallest addressable part of the computer screen which we can control.

## Advantage of CG

- It provides tools for producing pictures of all real world concrete objects as well as abstract objects.
- It can be used to create computer animation.
- We can have full control over the details of the graphics like, speed of animation, details of pictures, etc.
- CG provides the ability to update the object(Udate dynamics) and move objects respective to a observer(motion dynamics).

## Components of Computer Graphics

- There are 3 components of a interactive computer garphics:-
    - Digital Memory Buffer(Frame Buffer)
        - Frame Buffer is the Video-RAM(V-RAM) that is used to hold or map the image displayed on the screen.
        - The memory used to hold the image in Frame Buffer depends upon the resolution of screen and color depth used per pixel.

        ```    
        MB = (X-resolution * Y-resolution * Bits per pixel)/8 * 1024 * 1024
        ```
        - It is implement by rotating random access semiconductor memory, or by using shift registers.

    - TV monitor
        - It helps to display the graphics.
    - Display Controller
        - It is an interface between digital memory buffer and TV monitor.
        - Its main fucntion is to pass the contents of Frame buffer, convert those 0's and 1's into corresponding video signal, whch is fed to the TV monitor.
        - It is called as display card.
        - Example: VGA card, etc.

## Application of Computer graphics

- Computer Aided Design/Drafting (CAD and CADD)
    - It is used in CAD for designing process, mainly for engineering applications such as building and other structures.
    - 2D modelling to 3D modeling of objects, viewing from inside out, rotating to every angle and viewing in wireframe mode, all helps in more efficient CAD and CADD.
- Presentation graphics
    - Computer Graphics has also impacted alot in the presentation. It makes the presentation more condensed and impactful without having to incorporate slides and transition effects.
    - Many packages like spreedsheets, database management systems has also started to create graphical graphs for presenting large datas more efficiently. 
- Computer Art
    - The ability to use any amount of space, shapes, and different colors one can imagine, CG has provided artists a wonderful palate and paintbrush with the canvas to paint freely.
- Internet
    - CG is everywhere in internet from high-quality videos in youtube to music in spotify, all are CG and they are everywhere on the web. 
- Graphical User Interface(GUI)
    - Every packages of software nowadays have GUI in them, whether it be the icons of the app or menus, lists or guides provided, all are CG.
    - It helps to make the app more interactive and user friendly.
- Graphical Infromation System(GIS)
    - CG has the brought following capabilites in GIS:-
        - To apply graphical mathematics and query logic to extract and display various situation and conclusions.
        - To pictorially and scientifically in scale depict data and logical information in various forms on demand.
        - To register and superpose graphical layers from various sources, according to specified criteria.
        