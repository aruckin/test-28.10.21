package view;

import java.awt.EventQueue;

import javax.swing.JFrame;
import javax.swing.JButton;
import java.awt.event.ActionListener;
import java.awt.event.ActionEvent;
import java.awt.Color;
import javax.swing.JLabel;
import javax.swing.JOptionPane;
import javax.swing.BoxLayout;
import javax.swing.JRadioButton;
import javax.swing.ImageIcon;

public class Gui1 {
	
	private JFrame frmTest;
	private int zaeler=0;
	
	
	private JLabel lblFrage1;
	private JRadioButton rdbtnNewRadioButton_1;
	private JRadioButton rdbtnNewRadioButton_2;
	private JRadioButton rdbtnNewRadioButton_3;
	private JRadioButton rdbtnNewRadioButton_4;
	private JRadioButton rdbtnNewRadioButton_5;
	private JRadioButton rdbtnNewRadioButton_6;
	private JLabel lblNewLabel;
	private JRadioButton rdbtnNewRadioButton_7;
	private JRadioButton rdbtnNewRadioButton_8;
	private JRadioButton rdbtnNewRadioButton_9;
	private JRadioButton rdbtnNewRadioButton_10;
	private JRadioButton rdbtnNewRadioButton_11;
	private JRadioButton rdbtnNewRadioButton_12;
	private JLabel lblNewLabel_1;
	private JRadioButton rdbtnNewRadioButton_13;
	private JRadioButton rdbtnNewRadioButton_14;
	private JRadioButton rdbtnNewRadioButton_15;
	private JRadioButton rdbtnNewRadioButton_16;
	private JRadioButton rdbtnNewRadioButton_17;
	private JRadioButton rdbtnNewRadioButton_18;
	private JLabel lblNewLabel_2;
	private JRadioButton rdbtnNewRadioButton_19;
	private JRadioButton rdbtnNewRadioButton_20;
	private JRadioButton rdbtnNewRadioButton_21;
	private JRadioButton rdbtnNewRadioButton_22;
	private JRadioButton rdbtnNewRadioButton_23;
	private JRadioButton rdbtnNewRadioButton_24;
	private JLabel lblNewLabel_3;
	private JRadioButton rdbtnNewRadioButton_25;
	private JRadioButton rdbtnNewRadioButton_26;
	private JRadioButton rdbtnNewRadioButton_27;
	private JRadioButton rdbtnNewRadioButton_28;
	private JRadioButton rdbtnNewRadioButton;
	private JRadioButton rdbtnNewRadioButton_30;
	private JButton btnAuswerten;
	private final JRadioButton rdbtnSelten = new JRadioButton("selten");

	/**
	 * Launch the application.
	 */
	public static void main(String[] args) {
		EventQueue.invokeLater(new Runnable() {
			public void run() {
				try {
					Gui1 window = new Gui1();
					window.frmTest.setVisible(true);
				} catch (Exception e) {
					e.printStackTrace();
				}
			}
		});
	}

	/**
	 * Create the application.
	 */
	public Gui1() {
		initialize();
	}

	/**
	 * Initialize the contents of the frame.
	 */
	private void initialize() {
		frmTest = new JFrame();
		frmTest.setBackground(Color.LIGHT_GRAY);
		frmTest.getContentPane().setForeground(Color.BLACK);
		frmTest.setForeground(Color.BLACK);
		frmTest.setTitle("Test");
		frmTest.setBounds(100, 100, 600, 1203);
		frmTest.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frmTest.getContentPane().setLayout(new BoxLayout(frmTest.getContentPane(), BoxLayout.Y_AXIS));

		btnAuswerten = new JButton("Result");
		btnAuswerten.setForeground(Color.BLACK);
		
		frmTest.getContentPane().add(btnAuswerten);

		lblFrage1 = new JLabel("1. Wie oft waren Sie in den vergangenen 4 Wochen gluecklich?");
		frmTest.getContentPane().add(lblFrage1);

		rdbtnNewRadioButton_1 = new JRadioButton("");
		rdbtnNewRadioButton_1.setIcon(new ImageIcon("C:\\Users\\HomeTN\\Pictures\\stern-5.png"));
		rdbtnNewRadioButton_1.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				zaeler=zaeler+27;
				//für jede radiobutton Actionlistener schreiben???
			}
		});
		frmTest.getContentPane().add(rdbtnNewRadioButton_1);

		rdbtnNewRadioButton_2 = new JRadioButton("meistens");
		frmTest.getContentPane().add(rdbtnNewRadioButton_2);

		rdbtnNewRadioButton_3 = new JRadioButton("oft");
		frmTest.getContentPane().add(rdbtnNewRadioButton_3);

		rdbtnNewRadioButton_4 = new JRadioButton("manchmal");
		frmTest.getContentPane().add(rdbtnNewRadioButton_4);

		rdbtnNewRadioButton_5 = new JRadioButton("selten");
		frmTest.getContentPane().add(rdbtnNewRadioButton_5);

		rdbtnNewRadioButton_6 = new JRadioButton("nie");
		frmTest.getContentPane().add(rdbtnNewRadioButton_6);

		lblNewLabel = new JLabel("2. Wie oft haben Sie sich in den vergangenen 4 Wochen ruhig und gelassen gef\u00FChlt?");
		frmTest.getContentPane().add(lblNewLabel);

		rdbtnNewRadioButton_7 = new JRadioButton("immer");
		frmTest.getContentPane().add(rdbtnNewRadioButton_7);

		rdbtnNewRadioButton_8 = new JRadioButton("meistens");
		frmTest.getContentPane().add(rdbtnNewRadioButton_8);

		rdbtnNewRadioButton_9 = new JRadioButton("oft");
		frmTest.getContentPane().add(rdbtnNewRadioButton_9);

		rdbtnNewRadioButton_10 = new JRadioButton("manchmal");
		frmTest.getContentPane().add(rdbtnNewRadioButton_10);

		rdbtnNewRadioButton_11 = new JRadioButton("selten");
		frmTest.getContentPane().add(rdbtnNewRadioButton_11);

		rdbtnNewRadioButton_12 = new JRadioButton("nie");
		frmTest.getContentPane().add(rdbtnNewRadioButton_12);

		lblNewLabel_1 = new JLabel("3. Wie oft waren Sie in den vergangenen 4 Wochen sehr nerv\u00F6s?");
		frmTest.getContentPane().add(lblNewLabel_1);

		rdbtnNewRadioButton_13 = new JRadioButton("immer");
		frmTest.getContentPane().add(rdbtnNewRadioButton_13);

		rdbtnNewRadioButton_14 = new JRadioButton("meistens");
		frmTest.getContentPane().add(rdbtnNewRadioButton_14);

		rdbtnNewRadioButton_15 = new JRadioButton("oft");
		frmTest.getContentPane().add(rdbtnNewRadioButton_15);

		rdbtnNewRadioButton_16 = new JRadioButton("manchmal");
		frmTest.getContentPane().add(rdbtnNewRadioButton_16);

		rdbtnNewRadioButton_17 = new JRadioButton("selten");
		frmTest.getContentPane().add(rdbtnNewRadioButton_17);

		rdbtnNewRadioButton_18 = new JRadioButton("nie");
		frmTest.getContentPane().add(rdbtnNewRadioButton_18);

		lblNewLabel_2 = new JLabel("4. Wie oft f\u00FChlten Sie sich in den vergangenen 4 Wochen entmutigt und traurig?");
		frmTest.getContentPane().add(lblNewLabel_2);

		rdbtnNewRadioButton_19 = new JRadioButton("immer");
		frmTest.getContentPane().add(rdbtnNewRadioButton_19);

		rdbtnNewRadioButton_20 = new JRadioButton("meistens");
		frmTest.getContentPane().add(rdbtnNewRadioButton_20);

		rdbtnNewRadioButton_21 = new JRadioButton("oft");
		frmTest.getContentPane().add(rdbtnNewRadioButton_21);

		rdbtnNewRadioButton_22 = new JRadioButton("manchmal");
		frmTest.getContentPane().add(rdbtnNewRadioButton_22);

		rdbtnNewRadioButton_23 = new JRadioButton("selten");
		frmTest.getContentPane().add(rdbtnNewRadioButton_23);

		rdbtnNewRadioButton_24 = new JRadioButton("nie");
		frmTest.getContentPane().add(rdbtnNewRadioButton_24);

		lblNewLabel_3 = new JLabel("5. Wie oft waren Sie in den vergangenen 4 Wochen so niedergeschlagen, dass Sie nichts aufheitern konnte?");
		frmTest.getContentPane().add(lblNewLabel_3);

		rdbtnNewRadioButton_25 = new JRadioButton("immer");
		frmTest.getContentPane().add(rdbtnNewRadioButton_25);

		rdbtnNewRadioButton_26 = new JRadioButton("meistens");
		frmTest.getContentPane().add(rdbtnNewRadioButton_26);

		rdbtnNewRadioButton_27 = new JRadioButton("oft");
		frmTest.getContentPane().add(rdbtnNewRadioButton_27);

		rdbtnNewRadioButton_28 = new JRadioButton("manchmal");
		frmTest.getContentPane().add(rdbtnNewRadioButton_28);
		frmTest.getContentPane().add(rdbtnSelten);

		rdbtnNewRadioButton = new JRadioButton("selten");
		frmTest.getContentPane().add(rdbtnNewRadioButton);

		rdbtnNewRadioButton_30 = new JRadioButton("nie");
		frmTest.getContentPane().add(rdbtnNewRadioButton_30);

		btnAuswerten.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				if(zaeler>24) {
					JOptionPane.showMessageDialog(null, "Sehr gut!!!");
					//hier weitere else if varianten noch 4!!!
				}
				

			}
		});
		/*
		 * Auswertung
		 * 
		 * 1 - 6 Punkten
		 * 6 -- 30 Scala 
		 * 
		 * 25 punktenzahl( sinnvole teilung??  /5!!
		 * Teilen auf 5 caseblöcke
		 * 
		 * Ausgabe
		 * 
		 *  switch punktenzahl
		 *  	25-30		: sehr gut
		 *  	20-25		: gut
		 *  	15-19		: usw.
		 *  	10-14		: usw.
		 *  	5-9			: usw.
		 */
		
		/*
		 * 
		 */
	}
}
