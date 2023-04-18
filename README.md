The Planet Class
This class represents a celestial body in our solar system. Each Planet object has the following attributes:

x and y: The planet's position in the solar system (in meters)
radius: The radius of the planet (in pixels) for visualization purposes
color: The color of the planet
mass: The mass of the planet (in kg)
Additionally, the class includes the following methods:

draw(self, win)
This method draws the planet and its orbit on the Pygame window win. If the Planet object is not the Sun, it also displays the distance to the Sun in kilometers.

attraction(self, other)
This method calculates the gravitational force between the Planet object and another Planet object other. It returns the force components in the x and y directions.

update_pos(self, planets)
This method updates the position and velocity of the Planet object based on the gravitational forces from all other planets in the planets list. It also stores the new position in the orbit attribute.

The main() Function
The main() function initializes Pygame, sets up the display window, and creates instances of the Sun and the planets. It then enters the main simulation loop, where it:

Processes Pygame events (e.g., closing the window)
Updates the positions of the planets
Draws the planets and their orbits on the window
Updates the display
To run the simulation, save the code in a Python script file and execute the script. A window should open, displaying the orbits of the inner planets in our solar system. Enjoy exploring the beauty of our cosmic neighborhood!
