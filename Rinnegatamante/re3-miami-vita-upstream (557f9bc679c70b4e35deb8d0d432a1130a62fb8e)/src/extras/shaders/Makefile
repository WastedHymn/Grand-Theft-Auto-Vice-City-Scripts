all: im2d_gl.inc simple_fs_gl.inc default_UV2_gl.inc \
	colourfilterVC_fs_gl.inc contrast_fs_gl.inc \
	neoRim_gl.inc neoRimSkin_gl.inc \
	neoWorldVC_fs_gl.inc neoGloss_vs_gl.inc neoGloss_fs_gl.inc \
	neoVehicle_vs_gl.inc neoVehicle_fs_gl.inc \
	im2d_UV2_gl.inc screenDroplet_fs_gl.inc

im2d_gl.inc: im2d.vert
	(echo 'const char *im2d_vert_src =';\
	 sed 's/..*/"&\\n"/' im2d.vert;\
	 echo ';') >im2d_gl.inc

colourfilterVC_fs_gl.inc: colourfilterVC.frag
	(echo 'const char *colourfilterVC_frag_src =';\
	 sed 's/..*/"&\\n"/' colourfilterVC.frag;\
	 echo ';') >colourfilterVC_fs_gl.inc
simple_fs_gl.inc: simple.frag
	(echo 'const char *simple_frag_src =';\
	 sed 's/..*/"&\\n"/' simple.frag;\
	 echo ';') >simple_fs_gl.inc

default_UV2_gl.inc: default_UV2.vert
	(echo 'const char *default_UV2_vert_src =';\
	 sed 's/..*/"&\\n"/' default_UV2.vert;\
	 echo ';') >default_UV2_gl.inc



contrast_fs_gl.inc: contrast.frag
	(echo 'const char *contrast_frag_src =';\
	 sed 's/..*/"&\\n"/' contrast.frag;\
	 echo ';') >contrast_fs_gl.inc


neoRim_gl.inc: neoRim.vert
	(echo 'const char *neoRim_vert_src =';\
	 sed 's/..*/"&\\n"/' neoRim.vert;\
	 echo ';') >neoRim_gl.inc

neoRimSkin_gl.inc: neoRimSkin.vert
	(echo 'const char *neoRimSkin_vert_src =';\
	 sed 's/..*/"&\\n"/' neoRimSkin.vert;\
	 echo ';') >neoRimSkin_gl.inc

neoWorldVC_fs_gl.inc: neoWorldVC.frag
	(echo 'const char *neoWorldVC_frag_src =';\
	 sed 's/..*/"&\\n"/' neoWorldVC.frag;\
	 echo ';') >neoWorldVC_fs_gl.inc

neoGloss_fs_gl.inc: neoGloss.frag
	(echo 'const char *neoGloss_frag_src =';\
	 sed 's/..*/"&\\n"/' neoGloss.frag;\
	 echo ';') >neoGloss_fs_gl.inc

neoGloss_vs_gl.inc: neoGloss.vert
	(echo 'const char *neoGloss_vert_src =';\
	 sed 's/..*/"&\\n"/' neoGloss.vert;\
	 echo ';') >neoGloss_vs_gl.inc

neoVehicle_vs_gl.inc: neoVehicle.vert
	(echo 'const char *neoVehicle_vert_src =';\
	 sed 's/..*/"&\\n"/' neoVehicle.vert;\
	 echo ';') >neoVehicle_vs_gl.inc

neoVehicle_fs_gl.inc: neoVehicle.frag
	(echo 'const char *neoVehicle_frag_src =';\
	 sed 's/..*/"&\\n"/' neoVehicle.frag;\
	 echo ';') >neoVehicle_fs_gl.inc

im2d_UV2_gl.inc: im2d_UV2.vert
	(echo 'const char *im2d_UV2_vert_src =';\
	 sed 's/..*/"&\\n"/' im2d_UV2.vert;\
	 echo ';') >im2d_UV2_gl.inc

screenDroplet_fs_gl.inc: screenDroplet.frag
	(echo 'const char *screenDroplet_frag_src =';\
	 sed 's/..*/"&\\n"/' screenDroplet.frag;\
	 echo ';') >screenDroplet_fs_gl.inc
