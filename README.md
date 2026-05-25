change " 192.168.1.100 " to server IP (laptop IP)

layout.html:
<a href="http://192.168.1.100:8000/menu.html" class="nav-btn">Tour Select</a>

menu.html:
<form action="http://192.168.1.100:8000/tour_retrieve" method="POST" autocomplete="off" class="menu-container">
