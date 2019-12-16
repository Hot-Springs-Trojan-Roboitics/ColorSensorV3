# Distinguishing Color using RGB Values

To distinguish colors using RGB values, you first have to understand how they work. They simply calculate how much Red, Blue, and Green are in a color and provide values accordingly. The values are scaled from 0 - 255. With 0 being absolutely no color, and 255 being full color. Black and White are able to be scaled with the absolute 0f no color being black(0, 0, 0) and the absolute of all colors being white (255, 255, 255).

Now with this knowledge we can scale the difference between Red and Blue values(Which we are trying to determine) around the color of Purple. This is becuase all instances of Red and Blue color will include no Green and that Purple contains 50% Red and 50% Blue.


Color   |   R%   G%   B%   |   RV   GV   BV   |

Red     |  100%  0%   0%   |  255,   0,   0   |

Blue    |   0%   0%  100%  |    0,   0, 255   |

Purple  |  100%  0%   0%   |127.5,   0, 127.5 |

The Table above demonstrates the values of Red, Blue and Purple
