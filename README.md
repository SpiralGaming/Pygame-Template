# Pygame-Template
# Code
```Python
from pygame import *
import pygame

#Main Window Code
init() #Initialize pygame
screen = display.set_mode((800,600)) #Set screen size
title = display.set_caption("Snakie") #Set window title
icon = image.load('snakie.png') #Load icon
display.set_icon(icon) #Set icon

running = True #Set running to true
while running: #Loop
    
    screen.fill((215,215,215)) #Fill screen with color RGB - red green blue
    
    #Check if window is closed
    for event in pygame.event.get():
        if event.type == QUIT:
            running = False

    #Update screen
    display.update()
```
