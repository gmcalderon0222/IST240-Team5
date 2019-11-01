# IST240-Team5

import java.awt.Color;
import java.awt.Rectangle;
import javax.swing.JButton;
import javax.swing.JPanel;


public class IntroPanel extends JPanel {
    
    JButton CreditsB, InstructsB, OptionsB, MainB;
    
    
    public IntroPanel() {
        super();
        setLayout(null);
        setBackground(Color.PINK);
        
        // Credits button
        CreditsB = new JButton("Credits");
        Rectangle cb = new Rectangle(100, 100, 100, 100);
        CreditsB.setBounds(cb);
        add(CreditsB);
        // Instructions button
        InstructsB = new JButton("Instructions");
        Rectangle ib = new Rectangle(275, 100, 150, 100);
        InstructsB.setBounds(ib);
        add(InstructsB);
        // Options button
        OptionsB = new JButton("Options");
        Rectangle ob = new Rectangle(500, 100, 100, 100);
        OptionsB.setBounds(ob);
        add(OptionsB);
        
        MainB = new JButton("Main");
        Rectangle mb = new Rectangle(275, 250, 150, 100);
        MainB.setBounds(mb);
        add(MainB);
    }
    
}
