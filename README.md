Okvis -> windows
1)	�time�: 
	a.	Time (depend�ncia interna)
		i.	Em propriedades -> diret�rio de inclus�o adc: okvis_time\include

2)	� kinematics� : 
	a.	Gteste (dependencia externa)
		i.	em pr�-processador _USE_MATH_DEFINES
		ii.	Em propriedades -> diret�rio de inclus�o adc: include\gteste
		iii.	https://github.com/google/googletest

	b.	Eigen3 (dependencia externa)
		i.	modifica��o de __inline__ para inline
		ii.	Em propriedades -> diret�rio de inclus�o adc: include\eigen
		iii.	http://eigen.tuxfamily.org/index.php?title=Main_Page

	c.	Kinematics (depend�ncia interna)
		i.	Em propriedades -> diret�rio de inclus�o adc: include\kinematics

3)	�util�
	a.	Util (depend�ncia interna)
		i.	Em propriedades -> diret�rio de inclus�o adc: include\util
