# ME433_HC_HW6
Total pixels 128*128
Pixel per character:8*5
Total number of characters on screen: (128*128)/(8*5)=409.6

Per row total pixels 8*128
Max characters = (8*128)/(8*5)=25.6

number of ticks to turn on 5 pixels: 
(fps based on progressbar that increments by 1% every 0.2s)
fps=24000000/ticks
ticks=24000000/60 = 400000

for entire row ticks = 400000*128 = 51200000

seconds to fill row = 51200000 * 1/24000000 = 2.13s
