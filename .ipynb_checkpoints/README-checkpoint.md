The dataset comes from a RC plane that registered its route. The aim is to create its route and plot it
on the map. For that, we will use ```folium```. The dataset has a lot of information, however, we're going
to use only GPS coordinates. The reason for multiple GPS columns is that the plane's computer treated each sensor separately, hence
I calculated the average of lat & lon.