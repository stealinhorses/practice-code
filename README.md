practice-code
=============
public class Flower
{
   private int x;
   private int y;
   
   public Flower(int theX, int theY)
   {
     x = theX;
     y = theY;
   }
   /**
   * This function draws the flower.
   */
   public void draw()
   {Ellipse petalA = new Ellipse(x+20, y, 20, 20);
        petalA.setColor(Color.PINK);
        petalA.fill();
    
        Ellipse petalB = new Ellipse(x, y+20, 20, 20);
        petalB.setColor(Color.PINK);
        petalB.fill();
       
        Ellipse petalC = new Ellipse(x+20, y+20, 20, 20);
        petalC.setColor(Color.YELLOW);
        petalC.fill();
       
        Ellipse petalD = new Ellipse(x+40, y+20, 20, 20);
        petalD.setColor(Color.PINK);
        petalD.fill();
       
        Ellipse petalE = new Ellipse(x+20, y+40, 20, 20);
        petalE.setColor(Color.PINK);
        petalE.fill();
       
       Line stem = new Line(60, 90, 60, 150);
       stem.setColor(Color.GREEN);
       stem.draw();
    
       Line stem2 = new Line(x+30,y+60,x+30,y+120);
       stem2.setColor(Color.GREEN);
       stem2.draw();
   }
       
   
   
    
}
