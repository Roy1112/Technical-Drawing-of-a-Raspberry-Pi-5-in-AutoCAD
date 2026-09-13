# Technical Drawing of a Raspberry Pi 5 in AutoCAD

### Project Approach
<img width="284" height="185" alt="image" src="https://github.com/user-attachments/assets/7f9686ed-5b11-48cb-bff7-8f9af5dd2872" /><br>

This project aims to improve and demonstrate my technical drawing skills by reproducing a drawing created by Raspberry Pi Ltd. I followed the original drawing as closely as possible, including its dimensions. However, rather than directly copying the technical drawing provided by the company, I created my drawing based on photographs of the Raspberry Pi 5 shown on the company’s homepage. Consequently, some components may not look exactly the same as those shown in the company’s original drawing, as illustrated below.<br>

<img width="1289" height="561" alt="image" src="https://github.com/user-attachments/assets/ac3765b3-ba2c-49f9-929d-52227019db9a" /><br>



### Drawing Setup
<img width="582" height="384" alt="image" src="https://github.com/user-attachments/assets/760c205e-f188-42f3-8179-111c88cc118e" /><br>

Five additional layers were created for the drawing:<br>

- Frame
- Board
- Component
- Auxiliary Line
- Dimension

The **Frame** layer contains gray lines that define the printable boundary and provide a designated area for text. The **Board** layer contains green lines representing the PCB outline. The **Component** layer contains white lines representing the components. The **Auxiliary Line** layer is used solely for reference purposes and is not intended for printing. The **Dimension** layer contains the dimensional annotations, which are displayed in red.<br>

Different lineweights are assigned to each layer to improve the overall readability and visual hierarchy of the drawing.<br>
The outermost blue frame is placed on the **Defpoints** layer and is used to define the drawing window for the A4 sheet.<br>


### Drawing Methodology

The drawing process began by creating an A4-sized rectangle to establish the overall sheet boundary. A second rectangle was then created, with both its width and length 20 mm smaller than those of the A4 sheet. This inner rectangle defined the available drawing area. Dedicated areas for text were also created after this.<br>

Subsequently, the PCB outline was constructed based on the provided dimensions. The mounting holes were then positioned. Auxiliary construction lines were used during this process to establish the necessary reference points.<br>

The components were then drawn. Since dimensional information for the individual components was not provided, their sizes and positions were estimated based on the actual photograph. Therefore, the component geometry does not necessarily represent the actual dimensions of the components or exactly match the geometry used in the company's drawing.<br>

Finally, the specified dimensions and annotations were added to the drawing. The final PDF was configured to print at a 1:1 scale on A4 paper. All colored lines were changed to black, except for those that were intentionally shown in color in the company's drawing, in order to maintain consistency with the original.<br>
