# prank-pythhon-project
python code   


import pygame
from time import sleep
pygame.init()
window = pygame.display.set_mode((0, 0), pygame.FULLSCREEN)

pygame.mixer.init()
pygame.mixer.music.load('ratsasan.mp3.mpeg')
pygame.mixer.music.play()
sleep(5)

pygame.mixer.music.load('scary.mp3.mpeg')
pygame.mixer.music.play()

image = pygame.image.load('scr.jpg2.jpg')
window.blit(image, (0, 0))
pygame.display.update()
sleep(3)

