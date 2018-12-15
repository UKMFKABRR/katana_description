# katana_description

roslaunch katana_description katana_urdf_visualize.launch model:='$(find katana_description)/urdf/katana_450_6m90a_simple.urdf'

roslaunch katana_description katana_rviz.launch model:=katana_450_6m90a_simple.urdf

roslaunch katana_description spawn_katana_with_controllers.launch



