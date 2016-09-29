JFDML JFormDesigner: "5.2.4.0.321" Java: "1.6.0_21" encoding: "UTF-8"

new FormModel {
	contentType: "form/swing"
	root: new FormRoot {
		add( new FormWindow( "javax.swing.JFrame", new FormLayoutManager( class org.jdesktop.layout.GroupLayout ) {
			"$horizontalGroup": "par l {seq l {space :::p, par t:::p {comp label10::::59:x, comp label8::::59:x, comp label7::::59:x, par l {par t:l::p {comp label4::::59:x, par l {par l:l::p {comp label1::::59:x, comp label2::::59:x}, comp label3::l:p:50:p}}, comp label5::l:p:41:p, comp label6::l:p::p}}, space :p:30:p, par l {par l:::p {seq {par l {par l:::p {comp textField1::::73:x, comp textField2::::73:x, comp textField4::::73:x}, comp textField3:::p:94:p}, space s:::p, par l {comp button1:::p::p, comp button2:::p::p}}, seq l {par t:::p {comp textField5::l:::x, comp comboBox1::l:::x}, space u:::p, comp label9:::p::p, space s:::p, comp textField6:::::x}}, seq l {comp textField7:::p:65:p, space u:::p, par l {seq {comp button3:::p::p, space u:::p, comp button4:::p::p, space :::p, comp button5:::p::p}, seq {comp label11:::p:68:p, space :::p, comp textField8:::p:55:p}}}}, space ::21:x}}"
			"$verticalGroup": "par l {seq l {space :p:38:p, comp label1:::p::p, space u:::p, par b {comp label2::b:p::p, comp textField1::b:p::p}, space u:::p, par b {comp label3::b:p::p, comp textField2::b:p::p}, space u:::p, par b {comp label4::b:p::p, comp button1::b:p::p, comp textField3::b:p::p}, space u:::p, par b {comp label5::b:p::p, comp button2::b:p::p, comp textField4::b:p::p}, space u:::p, par l {comp label6:::p::p, comp comboBox1:::::p}, space s:::p, comp label7:::p::p, space u:::p, par b {comp label8::b:p::p, comp textField5::b:p::p, comp label9::b:p::p, comp textField6::b:p::p}, space s:::p, par b {comp label10::b:p::p, comp textField7::b:p::p, comp label11::b:p::p, comp textField8::b:p::p}, space ::7:x, par b {comp button3::b:p::p, comp button4::b:p::p, comp button5::b:p::p}, space :::p}}"
		} ) {
			name: "frame1"
			add( new FormComponent( "javax.swing.JLabel" ) {
				name: "label1"
				"text": "contact"
			} )
			add( new FormComponent( "javax.swing.JLabel" ) {
				name: "label2"
				"text": "first name:"
			} )
			add( new FormComponent( "javax.swing.JTextField" ) {
				name: "textField1"
			} )
			add( new FormComponent( "javax.swing.JLabel" ) {
				name: "label3"
				"text": "sur name:"
			} )
			add( new FormComponent( "javax.swing.JTextField" ) {
				name: "textField2"
			} )
			add( new FormComponent( "javax.swing.JLabel" ) {
				name: "label4"
				"text": "street:"
			} )
			add( new FormComponent( "javax.swing.JTextField" ) {
				name: "textField3"
			} )
			add( new FormComponent( "javax.swing.JButton" ) {
				name: "button1"
				"text": "browse"
			} )
			add( new FormComponent( "javax.swing.JLabel" ) {
				name: "label5"
				"text": "city:"
			} )
			add( new FormComponent( "javax.swing.JButton" ) {
				name: "button2"
				"text": "browse"
			} )
			add( new FormComponent( "javax.swing.JTextField" ) {
				name: "textField4"
			} )
			add( new FormComponent( "javax.swing.JLabel" ) {
				name: "label6"
				"text": "street:"
			} )
			add( new FormComponent( "javax.swing.JComboBox" ) {
				name: "comboBox1"
				"model": new javax.swing.DefaultComboBoxModel {
					selectedItem: "choose"
					addElement( "choose" )
					addElement( "street 1" )
					addElement( "street 2" )
					addElement( "street 3" )
				}
			} )
			add( new FormComponent( "javax.swing.JLabel" ) {
				name: "label7"
				"text": "phone:"
			} )
			add( new FormComponent( "javax.swing.JLabel" ) {
				name: "label8"
				"text": "work phone"
			} )
			add( new FormComponent( "javax.swing.JTextField" ) {
				name: "textField5"
			} )
			add( new FormComponent( "javax.swing.JLabel" ) {
				name: "label9"
				"text": "skype"
			} )
			add( new FormComponent( "javax.swing.JTextField" ) {
				name: "textField6"
			} )
			add( new FormComponent( "javax.swing.JLabel" ) {
				name: "label10"
				"text": "cell phone"
			} )
			add( new FormComponent( "javax.swing.JTextField" ) {
				name: "textField7"
			} )
			add( new FormComponent( "javax.swing.JLabel" ) {
				name: "label11"
				"text": "home phone"
			} )
			add( new FormComponent( "javax.swing.JTextField" ) {
				name: "textField8"
			} )
			add( new FormComponent( "javax.swing.JButton" ) {
				name: "button3"
				"text": "OK"
			} )
			add( new FormComponent( "javax.swing.JButton" ) {
				name: "button4"
				"text": "Cancel"
			} )
			add( new FormComponent( "javax.swing.JButton" ) {
				name: "button5"
				"text": "Help"
			} )
		}, new FormLayoutConstraints( null ) {
			"location": new java.awt.Point( 0, 0 )
			"size": new java.awt.Dimension( 390, 390 )
		} )
	}
}
