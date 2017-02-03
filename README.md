//viacheslav borodin 
// 15464068 


import java.awt.Graphics;
import java.awt.Graphics2D;
import javax.swing.JFrame;
import java.awt.Color;
import javax.swing.JPanel;
import javax.swing.JComponent;
import static javax.swing.JFrame.EXIT_ON_CLOSE;


	
class rect extends JComponent{
public void paint(Graphics g) {
		
		// left hand side of board 2 corner boxes 9 street boxes 
	g.drawRect(10,10,70,70);
	g.drawRect(10,80, 70, 60);
	g.drawRect(10,140,70, 60);
	g.drawRect(10,200, 70, 60);
	g.drawRect(10,260, 70, 60);	
	g.drawRect(10,320, 70, 60);
	g.drawRect(10,380, 70, 60);
	g.drawRect(10,440, 70, 60);
	g.drawRect(10,500, 70, 60);
	g.drawRect(10,560, 70, 60);
	g.drawRect(10,620,70,70);
	
	g.drawLine(35, 30, 35, 80);
	g.drawLine(35, 30, 80, 30);
	
	g.drawLine(683, 0, 683 , 768);
	
	// top 9 boxes going across 
	g.drawRect(80,10,50,70);
	g.drawRect(130,10,50,70);
	g.drawRect(180,10,50,70);
	g.drawRect(230,10,50,70);
	g.drawRect(280,10,50,70);
	g.drawRect(330,10,50,70);
	g.drawRect(380,10,50,70);
	g.drawRect(430,10,50,70);
	g.drawRect(480,10,50,70);
	g.drawRect(530,10,50,70);
	g.drawRect(580,10,70,70);
	
	
	// 9 boxes going down right hand side including box in corner bottom hand right
	g.drawRect(580,80, 70, 60);
	g.drawRect(580,140,70, 60);
	g.drawRect(580,200, 70, 60);
	g.drawRect(580,260, 70, 60);	
	g.drawRect(580,320, 70, 60);
	g.drawRect(580,380, 70,60);
	g.drawRect(580,440, 70, 60);
	g.drawRect(580,500, 70, 60);
	g.drawRect(580,560, 70, 60);
	g.drawRect(580,620, 70, 70);
	
	
	// 9 boxes going across lower 
	g.drawRect(80,530,50,70);
	g.drawRect(130,530,50,70);
	g.drawRect(180,530,50,70);
	g.drawRect(230,530,50,70);
	g.drawRect(280,530,50,70);
	g.drawRect(330,530,50,70);
	g.drawRect(380,530,50,70);
	g.drawRect(430,530,50,70);
	g.drawRect(480,530,50,70);
	g.drawRect(530,530,50,70);
	
	
	
	
	
	
}
	
}
	
	

	

	
	public class TheSimpsons extends JPanel{
		
	public static void main(String[] args){
		
		// new frame created called frame
		JFrame frame = new JFrame();
		
		// size of frame width by height 
	    frame.setSize(1366, 768);
	    // title
		frame.setTitle("Monopoly");
		//shows the frame
		frame.setVisible(true);
		frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		
		// gets the rectangle boxes from rect class to display in frame 
		frame.getContentPane().add(new rect());
		
		//JPanel jp = new JPanel();
		
		
		//jp.setBackground(Color.lightGray);
		//frame.add(jp);
		
		
	

	}
	

	

	
}
