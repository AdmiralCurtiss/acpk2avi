
			       acpk2avi

		  Another convertor from CPK to AVI.
		 Copyright (C) 1997-1998, GANA, Nishi

0. �v����

	�Z�K�T�^�[���̃V�l�p�b�N (CPK) �̃p�\�R����ł̊ӏ܂◘�p�Ɋ�
	���ăZ�K�E�G���^�[�v���C�[�X�Ђ͌��F���Ă��܂���. ���̌��ɂ�
	�ẴZ�K��\�t�g�n�E�X�ւ̎���Ȃǂ͂�����������.

1. �͂��߂�

	�����, �Z�K�T�^�[���ň�ʓI�ɓ���Ƃ��Ďg���Ă���V�l�p�b�N
	�t�@�C���� Windows �� AVI �t�@�C���ɕϊ�������̂ł�. ��������
	�\�t�g�E�F�A�ɑ΂��钷���Ƃ��Ă�, 

		1) �����̂Ȃ� CPK �� WAV �� ADP ��ǉ����� AVI ���쐬�ł���
		2) ADP �� WAV �֕ϊ��ł���
		3) �쐬����� AVI �̉����̈��k���ł���
		4) Windows95 OSR2 �ł������ƍĐ��ł��� AVI ���쐬����
		5) �쐬����� AVI �̃T�C�Y���኱������
		6) Win32 ���œ���

	�Ȃǂ�����܂�. 

2. �g����

	a) CPK �t�@�C������ AVI �t�@�C�����쐬��������
		acpk2avi [OPTIONS] <INPUT.cpk> <OUTPUT.avi>

	b) CPK �t�@�C���� ADP �t�@�C������ AVI �t�@�C�����쐬��������
		acpk2avi [OPTIONS] <INPUT.cpk> <INPUT.adp> <OUTPUT.avi>

	c) CPK �t�@�C���� WAV �t�@�C������ AVI �t�@�C�����쐬��������
		acpk2avi [OPTIONS] <INPUT.cpk> <INPUT.wav> <OUTPUT.avi>

	d) ADP �t�@�C������ WAV �t�@�C�����쐬��������
		acpk2avi <INPUT.adp> <OUTPUT.wav>

	e) �o�[�W���� 1.08 �ȑO�� acpk2avi �Ő������� AVI �t�@�C����, 
	   cpk2avi �ȂǂŐ������� AVI �t�@�C���� Windows95 OSR2 �ł���
	   ���ł���悤�ɂ�������
		acpk2avi [OPTIONS] <INPUT.avi> <OUTPUT.avi>
		acpk2avi [OPTIONS] <INPUT.avi> <INPUT.adp> <OUTPUT.avi>
		acpk2avi [OPTIONS] <INPUT.avi> <INPUT.wav> <OUTPUT.avi>

	[OPTIONS] �ɂ͈ȉ��̂��̂��w��ł��܂�. 
	
	-msadpcm	������ MS-ADPCM ���k���܂�. 
	-xaadpcm	�閧. -msadpcm �Ɠ����Ɏw�肷�邱�Ƃ͂ł��܂���. 
	+<DELAY>	�f���� <DELAY> �b�x�点�܂�. 
	-<DELAY>	������ <DELAY> �b�x�点�܂�. 
	-e<EXTEND>	�o�͂���� AVI �� <EXTEND> �b�������܂�. 
	-fps<FPS>	FPS(frame/sec) �l�� <FPS> ���Ɖ��肵�܂�. 
	-frequency<Hz>	�����̎��g���� <Hz> Hz ���Ɖ��肵�܂�. 
	-freq<Hz>			�V

	Windows 95 �� DOS ���� Windows NT �̃R�}���h�v�����v�g�Ȃǂ���
	�N�����Ă�������.

	�t�@�C�����͎Q�Ƃ��Ȃ��̂łǂ�ȃt�@�C�����ł����܂��܂���. ��
	���Ίg���q�� .ABS �ł����g�������Ƃ��� ADP �t�@�C���Ȃ� 
	<INPUT.adp> �̂Ƃ���Ɏw��ł��܂� (�u3. �g�p��v�̍Ō���Q��)

	-fps<FPS> �I�v�V������t���邱�Ƃɂ����, �����I�ɍĐ����� fps 
	�l��ݒ�ł��܂�. -fps24 �Ƃ����, 24 fps �ɐݒ肳��܂�. ����
	��, ���ۂ� fps ��菬�����l�ɂ���Ƃ܂Ƃ��ɍĐ��ł��Ȃ��ł���
	��. ���̃I�v�V������, acpk2avi �� fps �l�̎Z�o�Ɏ��s�����ꍇ��, 
	�K�؂Ȓl��ݒ肷��ړI�݂̂Ɏg���悤�ɂ��ׂ��ł�. ���Ȃ݂�, 
	fps �l�𑝂₵�Ă����炵�Ă��t�@�C���T�C�Y�͂قƂ�Ǖω����܂�
	��, ���₷�ƍĐ������������Ȃ�܂�. 

3. �g�p��

	�E�T�^�[���Łu�V���I�H���@���Q���I���v�� CD �� Q �h���C�u�ɓ�
	�ꂽ��Ԃ�, �ȉ��̂悤�ɂ����, �I�[�v�j���O�� AVI ���J�����g
	�f�B���N�g���ɍ쐬����܂�. 

	  acpk2avi.exe Q:\4001.CPK Q:\4000.ADP EvaOpening.avi

	�E�T�^�[���Łu�V���I�H���@���Q���I���v�� 4001.CPK �Ɖ��y CD ��
	�uNEON GENESIS EVANGELION II�v�̃g���b�N 2 (TRACK2.WAV) ����I�[
	�v�j���O���쐬 (TRACK2.WAV �� CD-DA �z�o���c�[���𗘗p���č쐬). 
	TRACK2.WAV �͎n�܂�^�C�~���O�����X�x���̂ŉf�����n�܂�̂�
	0.37 �b�قǑ��点�܂�. 

	  acpk2avi.exe +0.37 4001.CPK TRACK2.WAV EvaOpening.avi

	�E�T�^�[���Łu�@����̓i�f�c�R�`����ς�Ō�́w�������x?�`�v
	�̃G���f�B���O�� ADP �t�@�C���� WAV �ɕϊ�. 

	  acpk2avi.exe WATASI.ABS ���炵��.wav

4. ����

	�E���̃\�t�g�E�F�A�̓t���[�E�F�A�ł�. ���̃\�t�g�E�F�A�Ɋ֌W��
	��/���Ȃ��Ɋւ�炸, �����Ȃ邱�Ƃɂ��Ă���҂͐ӔC�𕉂���
	����. 

	�E�]�ڂȂǂ͌䎩�R�ɂǂ���. 

	�E���܂��ϊ��ł��Ȃ��V�l�p�b�N�����邩������܂���. ���̂Ƃ���
	���Ѝ�҂܂ŕ񍐂��Ă�������. �Ώ��ł��邩������܂���. 

	�EWAV ��������������Ƃ��� WAV �͂����� PCM �`���łȂ���΂Ȃ�
	�܂���. (PCM �`���ȊO���v�]������΃T�|�[�g���܂���, �����v�]
	�͂Ȃ��ł��傤 ^^;)

	�E�g���q�� ADP �̃t�@�C���ł��ϊ��ł��Ȃ����̂����邩�������
	����. �ϊ��ł�����, �u�V���I�H���@���Q���I���v��u�\��b�N
	JAM�v�Ȃǂł�. 

	�E�g���q�� ADP �łȂ��t�@�C���ł��ϊ��ł��鉹���t�@�C��������
	�܂�. �Ⴆ�΁u�@����̓i�f�c�R�v�ł͊g���q�� ACM �� ABS �̃t�@
	�C�����ϊ��ł��܂�. ��ʓI�ɂ�, �t�@�C���̐擪 48 �o�C�g��, ��
	���̌`���ɂȂ��Ă���Εϊ��ł���\��������܂�. 

0x00000000: 46 4f 52 4d .. .. .. .. - 41 49 46 46 43 4f 4d 4d FORM....AIFFCOMM
0x00000010: .. .. .. .. .. .. .. .. - .. .. .. .. .. .. .. .. ................
0x00000020: .. .. .. .. .. .. 41 50 - 43 4d .. .. .. .. .. .. ......APCM......

	"." �̏��͂Ȃ�ł������ł�. AIFF �t�@�C���� ADPCM �`���ł���. 

	�E�ŋ߂ł�, CPK �𒼐ڍĐ�/�ϊ��ł��� windvt2 (WV_102.LZH) (�V�F
	�A�E�F�A) �Ȃ�\�t�g�����݂���悤�ł�. acpk2avi �̑��݈Ӌ`��
	���񂾂񔖂�Ă��܂�����. 

	�Eadp2wav.c �̑S�Ă̌����� Nishi �����ۗL��, GANA �͂قƂ�ǎ�
	�������Ă���܂��� (���s�R�[�h��ς�������). �� ADP �t�@�C����
	�� WAV �t�@�C�����쐬���鎞��, acp2wav �����̂܂܋N�����Ă���
	�̂Ɠ�����������܂�. adp2wav ���肪�Ƃ��������܂� :) ��Nishi

	�E�u�V���I�H���@���Q���I��2nd�v�� 1000 �ԑ�, 2000 �ԑ�� CPK 
	�t�@�C���͕ϊ��ł��܂���. �����, CPK �Ƃ����g���q�ł͂��邯��, 
	�V�l�p�b�N�ł͂Ȃ��t�@�C��������ł�. �� 5105, 5267�`5271 �Ԃ�
	���܂��ϊ��ł��ĂȂ��悤�Ɍ����܂���, ���X���������f�[�^�Ȃ̂�
	����������܂��� (���� acpk2avi �̃o�O�������肵�āc). 

	�Eversion 1.11 �ȑO�ł� -msadpcm �I�v�V����������ƃA�N�e�B
	�u���[�r�[�ł܂Ƃ��ɍĐ��ł��Ȃ��t�@�C�����쐬����Ă��܂���. 
	�Ă�����A�N�e�B�u���[�r�[�̃o�O���Ǝv�����̂ł���, Nishi ����
	�w�E�ɂ�� acpk2avi �̃o�O���Ƃ������Ƃ��������܂���. ��������
	��ł��߂�Ȃ���m(__)m���A�N�e�B�u���[�r�[. 

	�E�ŋ߃T�^�[���ł� TrueMotion �������g����悤�ɂȂ��Ă��܂�
	����, TrueMotion �ɂ͑Ή��ł��܂���. �������炩�̎����������
	�Ή��ł��邩���m��܂���, ����ł͖����ł�. Windows �ōĐ���
	�\�� TrueMotion 2.0 �� AVI �ł�����Ή�͂ł��邩������Ȃ���
	�ł����c�ł��Z�����̂Ŗ����ł��傤.

5. �Q�l�ɂ�������

	�Ecpk2avi �Ő������ꂽ AVI �t�@�C��
	�EX Cinepack Player �̃\�[�X
	�Eadp2wav �̃\�[�X
	�Ewaveconv �̒��� msadpcm.c
	�EVideo for Windows �̃h�L�������g
	�ȂǂȂ�

6. �R���p�C�����@

	acpk2avi.exe �� Windows95/NT �p�ł���, �R���p�C���������� UNIX 
	�Ȃǂł������܂�. Makefile ���኱�C������, �K�v�Ȃ�Ε���
	�R�[�h��ύX���邾���ŃR���p�C���ł���ł��傤.

	acpk2avi.exe �� Visual C++ 5.0 ���C���X�g�[������Ă����, 

	C:\acpk2avi\source\> nmake -f Makefile.vc nodebug=1

	�ȂǂƂ���΍쐬�ł��܂�. (������ acpk2avi.exe �͏�L�̂悤��
	���č쐬����Ă��܂�)

	�ȉ��̊��ł�, 

		Cygnus GNU-Win32-b18
		Debian GNU/Linux
		Solaris

	% make -f Makefile.gcc

	�ȂǂƂ��邾���ō쐬�ł��܂�. 

	��, SunOS4 �ł� memmove �֐����Ȃ��̂ŃR���p�C���ł��܂���. 
	(memmove ���炢�����ŏ����΂����ł��� ^^;) ������ UNIX �ŃR��
	�p�C���ł��Ă�, xanim �ł͂��܂��Đ��ł��Ȃ��ꍇ�������̂ł���
	�肤�ꂵ���͂Ȃ��̂ł���. 

7. ���

	GANA - acpk2avi ���쐬
		TAGA Nayuta <nayuta@is.s.u-tokyo.ac.jp>

	Nishi - adp2wav ���쐬
		Nobuyuki Nishizawa <nishi@gavo.t.u-tokyo.ac.jp>

8. �T�|�[�g�z�[���y�[�W

	http://www.is.s.u-tokyo.ac.jp/~nayuta/acpk2avi/index-j.html

9. ����

	version 1.00 1997/04/13

	version 1.01 1997/04/14
		�EbiSizeImage �̒l�� 0 �ɐݒ肷��悤�ɂ���. 
		�ERIFF chunk �� WORD �A���C�������g���������Y��Ă���
		�o�O�̏C��. 

	version 1.02 1997/05/01
		�E�����̓����Ă��Ȃ��V�l�p�b�N�ɑΉ�����. 

	version 1.03 1997/05/16
		�E�V�l�p�b�N�Ɖ����������ł���悤�ɂ���. 

	version 1.04 1997/05/19
		�EDELAY �@�\��t����. 
		�EMS-ADPCM �𒆓r���[�Ɏ�������. 

	version 1.05 1997/06/18
		�E��������� FLY.CPK �� FINAL.CPK �����܂��ϊ��ł���
		�������̂ɔ����C��. 

	version 1.06 1997/06/18
		�E�����̓����Ă��Ȃ��V�l�p�b�N��ϊ����悤�Ƃ���ƃG���[
		���o���o�O���C��. 

	version 1.07 1997/06/26
		�E8bit �̉����̃V�l�p�b�N��ϊ�����Ɖ������������Ȃ�
		�o�O���C��. 

	version 1.08 1997/07/17
		�E�X�e���I�̉��������E�t�ɂȂ��Ă��܂��o�O�̏C��. 
		�E-e<EXTEND> �I�v�V�����̒ǉ�. 
		�E�閧�̋@�\ -xaadpcm �̒ǉ�. (�g�����Ƃ��Ă��g������
		�킩��Ȃ��Ǝv���܂� ^^;)

	version 1.09 1997/07/18
		�EWindows95 OSR2 �ł͉摜���Đ��ł��Ȃ��o�O�̏C��. 

	version 1.10 1997/07/19
		�E�閧�̋@�\�̂����ō��������܂ʂ��ȃo�O�̑ގ�. 

	version 1.11 1997/08/02
		�Efps ���Z�o���� 60 fps �𒴂��邱�Ƃ��Ȃ��悤�ɂ���. 
		�Efps ��ݒ�ł���悤�ɂ���. 

	version 1.12 1997/08/10
		�EMS-ADPCM ���k�������̂��A�N�e�B�u���[�r�[�ł��܂���
		���ł���悤�ɂȂ���. (thanks to Nishi)

	version 1.13 1997/08/21
		�E�o�[�W���� 1.08 �ȑO�� acpk2avi �Ő������� AVI �t�@
		�C����, cpk2avi �ȂǂŐ������� AVI �t�@�C���� 
		Windows95 OSR2 �ł��Đ��ł���悤�ɕϊ��ł���悤�ɂȂ�
		��. 

	version 1.14 1997/09/05
		�EADP �t�@�C������ WAV �t�@�C�����쐬�ł��Ȃ��Ȃ��Ă�
		���o�O���C��. 

	version 1.15 1997/09/11
		�EAVI ���o�͂���ꍇ�ɉ����̎��g����ݒ�ł���悤�ɂ�
		��. 
		�EADP �t�@�C������ WAV �t�@�C�����쐬����ۂ̎��g���v
		�Z�ɂ�����, ���������_���Z�̃o�O�̏C�� (by Nishi). 

	version 1.16 1997/10/06
		�E8bit �̉����̃V�l�p�b�N�ŉ�����x�点��ƃm�C�Y������
		�Ă�����������Ȃ��o�O���C�����ꂽ��������Ȃ�.

	version 1.17 1997/11/14
		�E�v���ӂ�������.
		�EMakefile.vc ������.

	version 1.18 1997/12/08
		�EREADME.txt �̋L�ړ��e�̃~�X���C��.

	version 1.19 1998/01/27
		�Eavi ���� avi �ւ̃R���o�[�g����, 00dc �ł͂Ȃ� 00id 
		  �Ȃǂł��摜�`�����N�Ƃ݂Ȃ��悤�ɂ���.

								����:GANA
