import java.io.*;
import javax.swing.*;
import java.awt.*;
import java.awt.event.*;
public class Notepad implements ActionListener
{
 JFrame f1,f2,f3;
 Container c1,c2,c3;
 JTextField t2,t3,t4;
 JTextArea t1;
 JButton b1,b2,b3;
 JLabel l1,l2,l3,l4;
 JMenu m1,m2,m3,m4,m5;
 JMenuItem i1,i2,i3,i4,i5,i6,i7,i8,i9,i10,i11,i12,i13,i14,i15,i16;
 JMenuBar mb;
 Notepad()
 {
  f1=new JFrame("Untitled-Notepad");
  c1=f1.getContentPane();
  m1=new JMenu("File");
  m2=new JMenu("Edit");
  m3=new JMenu("Format");
  m4=new JMenu("View");
  m5=new JMenu("Help");
  i1=new JMenuItem("New");
  i1.addActionListener(this);
  i16=new JMenuItem("New Window");
  i16.addActionListener(this);
  i2=new JMenuItem("Open");
  i2.addActionListener(this);
  i3=new JMenuItem("Save");
  i3.addActionListener(this);
  i4=new JMenuItem("Print");
  i4.addActionListener(this);
  i5=new JMenuItem("Exit");
  i5.addActionListener(this);
  i6=new JMenuItem("Cut");
  i7=new JMenuItem("Copy");
  i8=new JMenuItem("Paste");
  i9=new JMenuItem("Word Wrap");
  i10=new JMenuItem("Font..");
  i11=new JMenuItem("Zoom");
  i12=new JMenuItem("Status Bar");
  i13=new JMenuItem("View Help");
  i14=new JMenuItem("Send Feedback");
  i15=new JMenuItem("About Notepad");
  m1.add(i1);
  m1.add(i16);
  m1.add(i2);
  m1.add(i3);
  m1.add(i4);
  m1.add(i5);
  m2.add(i6);
  m2.add(i7);
  m2.add(i8);
  m3.add(i9);
  m3.add(i10);
  m4.add(i11);
  m4.add(i12);
  m5.add(i13);
  m5.add(i14);
  m5.add(i15);
  mb=new JMenuBar();
  mb.add(m1);
  mb.add(m2);
  mb.add(m3);
  mb.add(m4);
  mb.add(m5);
  f1.setJMenuBar(mb);
  f1.setVisible(true);
  f1.setLayout(null);
  f1.setSize(500,500);
  c1.setBackground(Color.WHITE);
  t1=new JTextArea();
  t1.setBounds(0,0,500,500);
  c1.add(t1);
 }
 // main screen default screen 
 public void open()
 {
    f2=new JFrame("Notepad");
  l1=new JLabel("File name:");
  t2=new JTextField();
  t3=new JTextField();
  b1=new JButton("Open");
  c2=f2.getContentPane();
  f2.setLayout(null);
  f2.setVisible(true);
  f2.setSize(300,300);
  f2.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
  c2.setBackground(Color.WHITE);
  l1.setBounds(20,20,80,30);
  t2.setBounds(120,20,140,30);
  b1.setBounds(180,60,70,40);
  t3.setBounds(20,100,140,30);
  b1.addActionListener(this);
  c2.add(l1);
  c2.add(t2);
  c2.add(b1);
  c2.add(t3);
 }
 // when you open a new file 
 public void open1(String y2)
 {
  f1=new JFrame("Untitled-Notepad");
  c1=f1.getContentPane();
  m1=new JMenu("File");
  m2=new JMenu("Edit");
  m3=new JMenu("Format");
  m4=new JMenu("View");
  m5=new JMenu("Help");
  i1=new JMenuItem("New");
  i1.addActionListener(this);
  i16=new JMenuItem("New Window");
  i16.addActionListener(this);
  i2=new JMenuItem("Open");
  i2.addActionListener(this);
  i3=new JMenuItem("Save");
  i3.addActionListener(this);
  i4=new JMenuItem("Print");
  i4.addActionListener(this);
  i5=new JMenuItem("Exit");
  i5.addActionListener(this);
  i6=new JMenuItem("Cut");
  i7=new JMenuItem("Copy");
  i8=new JMenuItem("Paste");
  i9=new JMenuItem("Word Wrap");
  i10=new JMenuItem("Font..");
  i11=new JMenuItem("Zoom");
  i12=new JMenuItem("Status Bar");
  i13=new JMenuItem("View Help");
  i14=new JMenuItem("Send Feedback");
  i15=new JMenuItem("About Notepad");
  m1.add(i1);
  m1.add(i16);
  m1.add(i2);
  m1.add(i3);
  m1.add(i4);
  m1.add(i5);
  m2.add(i6);
  m2.add(i7);
  m2.add(i8);
  m3.add(i9);
  m3.add(i10);
  m4.add(i11);
  m4.add(i12);
  m5.add(i13);
  m5.add(i14);
  m5.add(i15);
  mb=new JMenuBar();
  mb.add(m1);
  mb.add(m2);
  mb.add(m3);
  mb.add(m4);
  mb.add(m5);
  f1.setJMenuBar(mb);
  f1.setVisible(true);
  f1.setLayout(null);
  f1.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
  f1.setSize(500,500);
  c1.setBackground(Color.WHITE);
  t1=new JTextArea();
  t1.setText(y2);
  t1.setBounds(0,0,500,500);
  c1.add(t1);
 }
 public void save()
{
  f3=new JFrame("Save as");
  c3=f3.getContentPane();
  l2=new JLabel("File name");
  l3=new JLabel();
  b2=new JButton("SAVE");
  b2.addActionListener(this);
  t3=new JTextField();
  f3.setLayout(null);
  f3.setVisible(true);
  f3.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
  f3.setSize(400,400);
  c3.setBackground(Color.WHITE);
  l2.setBounds(20,20,100,30);
  t3.setBounds(150,20,80,30);
  b2.setBounds(50,70,100,50);
  l3.setBounds(30,120,220,40);
  c3.add(l2);
  c3.add(b2);
  c3.add(l3);
  c3.add(t3);
 }
 public void actionPerformed(ActionEvent e)
  {
  if(e.getSource()==i1)
  {
   f1.dispose();
   new Notepad();
  }
  else if(e.getSource()==i16)
  {
   new Notepad();
  }
  else if(e.getSource()==i2)
  {
   open();
  }
  else if(e.getSource()==b1)
  {
   int i;
   String y1=new String();
   String y2=new String();
   y1=t2.getText();
   try
   {
    FileInputStream fin=new FileInputStream(y1);
    while(true)
    {
     i=fin.read();
     if(i==-1)
      break;
     y2+=(char)(i);
    }
    open1(y2);
   }
   catch(Exception e1)
   {
    t3.setText("File Not Found");
   }
  }
  else if(e.getSource()==i3)
  {
   save();
  }
  else if(e.getSource()==b2)
  {
   try
   {
    int i,n;
    byte[] br=t1.getText().getBytes();
    FileOutputStream fout=new FileOutputStream(t3.getText());
    n=br.length;
    for(i=0;i<n;i++)
    {
     fout.write(br[i]);
    }
    fout.close();
    l3.setText("SUCCESSFULLY SAVED AS "+t3.getText());
   }
   catch(Exception e2)
   {
    System.out.println(e2);
   }
   
  }
  else if(e.getSource()==i5)
  {
    System.exit(0);
 }
 else if(e.getSource()==i10)
 {
    
 }
 }
 public static void main(String args[])
 {
  new Notepad();
 }
}
