# Unity_Scroll-View

![](Scroll.gif)

## Horizontal Scroll

1. Add a UI canvus
2. Make a empty object and add "Rect Transfrom", "Canvas Renderer" and "Horizontal Layout Group" component
3. In "Horizontal Layout Group" make "Child Alignment = Middle Center"
4. Add your sprites to the content that will be scrolled
5. Make Panel child of Canvas. Then Make Content child of the Panel (Order Will Be: Canvas -> Panel -> Content)
6. Add "Scroll Rect" component to the Panel and Disable Vertical if you only want Horizontal movement or Scroll.

## Masking

1. Add a image to the Panel
2. Name it "View"
3. Hold ALT + Shift and stretch the image to the size of the Panel from the "Rect Transfrom" (Botton Right Button) 
4. Make Content Child of the View. (Order Now: Canvas -> Panel -> View -> Content) 
5. Add "Musk" component to View.
6. Hold ALT and Drag the View to Fit your Panel so it looks better when scrolling

## Dynamic Content

1. Add "Content Size Fitter" component to your content
2. As it is Horizontal scroll, make "Horizontal Fit = Preferred Size"
