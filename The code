app.background = 'black'
Label('Game Score',60,10,fill='white',size=20,bold=True)
mark = Label(0,132,9,fill='white',size=20,bold=True)
H = Group()
H.add(
    Arc(15,200,21,21,135,270,fill='yellow'),
    Circle(11,197,3)
    )
H_left = Group(
    Arc(15,200,21,21,-45,270,fill='yellow'),
    Circle(20,197,3),
    visible = False
    )
# this is the instruction of create those ghost and define each ghost's speed,which is quicker or slower
g1 = Group(
    Circle(108,374,10,fill='hotpink'),
    Rect(98,374,20,10,fill='hotpink'),
    Circle(101,384,4,fill='hotpink'),
    Circle(108,384,4,fill='hotpink'),
    Circle(115,384,4,fill='hotpink'),
    Circle(103,371,4,fill='white'),
    Circle(112,371,4,fill='white'),
    Circle(103,371,2,fill='cyan'),
    Circle(112,371,2,fill='cyan'),
    )
g1.dx = 3
g1.dy = -3

g2 = Group(
    Circle(71,118,10,fill='springGreen'),
    Rect(61,118,20,10,fill='springGreen'),
    Circle(64,128,4,fill='springGreen'),
    Circle(71,128,4,fill='springGreen'),
    Circle(78,128,4,fill='springGreen'),
    Circle(66,115,4,fill='white'),
    Circle(75,115,4,fill='white'),
    Circle(66,115,2,fill='cyan'),
    Circle(75,115,2,fill='cyan'),
    )
g2.dx = -4
g2.dy = 4

g3 = Group(
    Circle(329,164,10,fill='deepSkyBlue'),
    Rect(319,164,20,10,fill='deepSkyBlue'),
    Circle(322,174,4,fill='deepSkyBlue'),
    Circle(329,174,4,fill='deepSkyBlue'),
    Circle(336,174,4,fill='deepSkyBlue'),
    Circle(324,161,4,fill='white'),
    Circle(333,161,4,fill='white'),
    Circle(324,161,2,fill='cyan'),
    Circle(333,161,2,fill='cyan'),
    )
g3.dy = 4
g3.dx = -4

g4 = Group(
    Circle(375,71,10,fill='red'),
    Rect(365,71,20,10,fill='red'),
    Circle(368,81,4,fill='red'),
    Circle(375,81,4,fill='red'),
    Circle(382,81,4,fill='red'),
    Circle(370,68,4,fill='white'),
    Circle(379,68,4,fill='white'),
    Circle(370,68,2,fill='cyan'),
    Circle(379,68,2,fill='cyan'),
    )
g4.dy = 3
g4.dx = -3
g5 = Group(
    Circle(90,255,10,fill='mediumSlateBlue'),
    Rect(80,255,20,10,fill='mediumSlateBlue'),
    Circle(83,265,4,fill='mediumSlateBlue'),
    Circle(90,265,4,fill='mediumSlateBlue'),
    Circle(97,265,4,fill='mediumSlateBlue'),
    Circle(85,252,4,fill='white'),
    Circle(94,252,4,fill='white'),
    Circle(85,252,2,fill='cyan'),
    Circle(94,252,2,fill='cyan'),
    )
g5.dx = 1
g5.dy = 1

g6 = Group(
    Circle(230,68,10,fill='lightSalmon'),
    Rect(220,68,20,10,fill='lightSalmon'),
    Circle(223,78,4,fill='lightSalmon'),
    Circle(230,78,4,fill='lightSalmon'),
    Circle(237,78,4,fill='lightSalmon'),
    Circle(225,65,4,fill='white'),
    Circle(234,65,4,fill='white'),
    Circle(225,65,2,fill='cyan'),
    Circle(234,65,2,fill='cyan'),
    )
g6.dy = 4
g6.dx = -4

g7 = Group(
    Circle(75,80,10,fill='orange'),
    Rect(65,80,20,10,fill='orange'),
    Circle(68,90,4,fill='orange'),
    Circle(75,90,4,fill='orange'),
    Circle(82,90,4,fill='orange'),
    Circle(70,77,4,fill='white'),
    Circle(79,77,4,fill='white'),
    Circle(70,77,2,fill='cyan'),
    Circle(79,77,2,fill='cyan'),
    )
g7.dx = 2
g7.dy = 2
#How to create the maze
w = Group()
w.add(
    Line(10, 20, 393, 20, fill='blue', lineWidth=3,opacity=40),
    Line(390, 20, 390, 400, fill='blue', lineWidth=3,opacity=40),
    Line(10,395,390,395,fill='blue', lineWidth=3,opacity=40),
    Line(10, 20, 10, 140, fill='blue', lineWidth=3,opacity=40),
    Line(10,140,50,140,fill='blue', lineWidth=3,opacity=40),
    Line(50,140,50,180,fill='blue', lineWidth=3,opacity=40),
    Line(50,180,0,180,fill='blue', lineWidth=3,opacity=40),
    Line(0, 220, 50,220, fill='blue', lineWidth=3,opacity=40),
    Line(0, 220, 50,220, fill='blue', lineWidth=3,opacity=40),
    Line(50, 220, 50,260, fill='blue', lineWidth=3,opacity=40),
    Line(50, 260,10,260, fill='blue', lineWidth=3,opacity=40),
    Line(10, 260,10,400, fill='blue', lineWidth=3,opacity=40),
    
    
    Line(7, 23, 390, 23, fill='blue', lineWidth=3),
    Line(393, 20, 393, 400, fill='blue', lineWidth=3),
    Line(10,395,393,395,fill='blue', lineWidth=3),
    Line(7, 20, 7, 140, fill='blue', lineWidth=3),
    Line(7, 143, 50, 143, fill='blue', lineWidth=3),
    Line(47, 143, 47, 180, fill='blue', lineWidth=3),
    Line(50, 183, 0, 183, fill='blue', lineWidth=3),
    Line(0, 223, 50,223, fill='blue', lineWidth=3),
    Line(47, 220, 47,260, fill='blue', lineWidth=3),
    Line(50, 263,7,263, fill='blue', lineWidth=3),
    Line(7, 260,7,400, fill='blue', lineWidth=3),
    
    Line(7,310,55,310,fill='blue', lineWidth=3,opacity=40),
    Line(7,313,55,313,fill='blue', lineWidth=3),
    Line(90,220,90,240,fill='blue', lineWidth=3,opacity=40),
    Line(93,220,93,240,fill='blue', lineWidth=3),
    Line(7,355,55,355,fill='blue', lineWidth=3,opacity=40),
    Line(7,358,55,358,fill='blue', lineWidth=3),
    Line(90,355,90,395,fill='blue', lineWidth=3,opacity=40),
    Line(93,355,93,395,fill='blue', lineWidth=3),
    Line(90,100,90,180,fill='blue', lineWidth=3,opacity=40),
    Line(93,100,93,180,fill='blue', lineWidth=3),
    Line(90,100,55,100,fill='blue', lineWidth=3,opacity=40),
    Line(90,103,55,103,fill='blue', lineWidth=3),
    Line(55,100,55,60,fill='blue', lineWidth=3),
    Line(58,100,58,60,fill='blue', lineWidth=3,opacity=40),
    Line(90,140,140,140,fill='blue', lineWidth=3,opacity=40),
    Line(90,143,140,143,fill='blue', lineWidth=3),
    Line(140,140,140,180,fill='blue', lineWidth=3,opacity=40),
    Line(143,140,143,180,fill='blue', lineWidth=3),
    Line(140,180,180,180,fill='blue', lineWidth=3,opacity=40),
    Line(140,183,180,183,fill='blue', lineWidth=3),
    Line(90,220,130,220,fill='blue', lineWidth=3,opacity=40),
    Line(90,223,130,223,fill='blue', lineWidth=3),
    Line(130,220,130,240,fill='blue', lineWidth=3,opacity=40),
    Line(133,220,133,240,fill='blue', lineWidth=3),
    Line(90,280,90,310,fill='blue', lineWidth=3,opacity=40),
    Line(93,280,93,310,fill='blue', lineWidth=3),
    Line(93,20,93,60,fill='blue', lineWidth=3,opacity=40),
    Line(96,20,96,60,fill='blue', lineWidth=3),
    Line(90,355,210,355,fill='blue', lineWidth=3,opacity=40),
    Line(90,358,210,358,fill='blue', lineWidth=3),
    Line(130,280,130,310,fill='blue', lineWidth=3,opacity=40),
    Line(133,280,133,310,fill='blue', lineWidth=3),
    Line(140,20,140,60,fill='blue', lineWidth=3,opacity=40),
    Line(143,20,143,60,fill='blue', lineWidth=3),
    Line(90,100,140,100,fill='blue', lineWidth=3,opacity=40),
    Line(90,103,140,103,fill='blue', lineWidth=3),
    Line(180,180,180,100,fill='blue', lineWidth=3,opacity=40),
    Line(177,180,177,100,fill='blue', lineWidth=3),
    Line(180,20,180,60,fill='blue', lineWidth=3,opacity=40),
    Line(177,20,177,60,fill='blue', lineWidth=3),
    Line(177,60,215,60,fill='blue', lineWidth=3,opacity=40),
    Line(177,57,215,57,fill='blue', lineWidth=3),
    Line(215,60,215,183,fill='blue', lineWidth=3,opacity=40),
    Line(212,60,212,183,fill='blue', lineWidth=3),
    Line(180,180,212,180,fill='blue', lineWidth=3,opacity=40),
    Line(180,183,212,183,fill='blue', lineWidth=3),
    Line(213,57,250,57,fill='blue', lineWidth=3),
    Line(213,60,250,60,fill='blue', lineWidth=3,opacity=40),
    Line(250,60,250,85,fill='blue', lineWidth=3,opacity=40),
    Line(247,60,247,85,fill='blue', lineWidth=3),
    Line(310,20,310,60,fill='blue', lineWidth=3,opacity=40),
    Line(307,20,307,60,fill='blue', lineWidth=3),
    Line(307,60,285,60,fill='blue', lineWidth=3,opacity=40),
    Line(307,57,285,57,fill='blue', lineWidth=3),
    Line(307,60,282,60,fill='blue', lineWidth=3,opacity=40),
    Line(307,57,282,57,fill='blue', lineWidth=3),
    Line(285,57,285,85,fill='blue', lineWidth=3,opacity=40),
    Line(282,57,282,85,fill='blue', lineWidth=3),
    Line(307,60,332,60,fill='blue', lineWidth=3,opacity=40),
    Line(307,57,332,57,fill='blue', lineWidth=3),
    Line(332,57,332,123,fill='blue', lineWidth=3,opacity=40),
    Line(330,57,330,123,fill='blue', lineWidth=3),
    Line(390,60,360,60,fill='blue', lineWidth=3,opacity=40),
    Line(390,57,360,57,fill='blue', lineWidth=3),
    Line(365,60,365,85,fill='blue', lineWidth=3,opacity=40),
    Line(362,60,362,85,fill='blue', lineWidth=3),
    Line(247,120,247,183,fill='blue', lineWidth=3),
    Line(250,120,250,183,fill='blue', lineWidth=3,opacity=40),
    Line(250,120,332,120,fill='blue', lineWidth=3,opacity=40),
    Line(250,123,332,123,fill='blue', lineWidth=3),
    Line(175,355,175,310,fill='blue', lineWidth=3,opacity=40),
    Line(172,355,172,310,fill='blue', lineWidth=3),
    Line(133,310,175,310,fill='blue', lineWidth=3,opacity=40),
    Line(133,307,175,307,fill='blue', lineWidth=3),
    Line(133,220,175,220,fill='blue', lineWidth=3,opacity=40),
    Line(133,223,175,223,fill='blue', lineWidth=3),
    Line(175,223,175,240,fill='blue', lineWidth=3,opacity=40),
    Line(172,223,172,240,fill='blue', lineWidth=3),
    Line(175,307,175,280,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(172,307,172,280,fill=rgb(0,0,255),lineWidth=3),
    Line(133,310,93,310,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(133,307,93,307,fill=rgb(0,0,255),lineWidth=3),
    Line(210,358,210,220,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(207,358,207,220,fill=rgb(0,0,255),lineWidth=3),
    Line(175,220,210,220,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(175,223,210,223,fill=rgb(0,0,255),lineWidth=3),
    Line(204,250,245,250,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(204,253,245,253,fill=rgb(0,0,255),lineWidth=3),
    Line(245,253,245,285,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(242,253,242,285,fill=rgb(0,0,255),lineWidth=3),
    Line(242,285,275,285,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(242,282,275,282,fill=rgb(0,0,255),lineWidth=3),
    Line(275,282,275,320,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(272,282,272,320,fill=rgb(0,0,255),lineWidth=3),
    Line(272,320,240,320,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(272,322,240,322,fill=rgb(0,0,255),lineWidth=3),
    Line(240,320,240,358,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(243,320,243,358,fill=rgb(0,0,255),lineWidth=3),
    Line(240,358,275,358,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(240,360,275,360,fill=rgb(0,0,255),lineWidth=3),
    Line(272,282,310,282,fill=rgb(0,0,255),lineWidth=3),
    Line(272,285,310,285,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(310,282,310,322,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(308,282,308,322,fill=rgb(0,0,255),lineWidth=3),
    Line(355,360,355,322,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(352,360,352,322,fill=rgb(0,0,255),lineWidth=3),
    Line(310,358,355,358,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(310,360,355,360,fill=rgb(0,0,255),lineWidth=3),
    Line(250,180,280,180,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(250,183,280,183,fill=rgb(0,0,255),lineWidth=3),
    Line(280,180,280,243,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(277,180,277,243,fill=rgb(0,0,255),lineWidth=3),
    Line(277,243,315,243,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(277,246,315,246,fill=rgb(0,0,255),lineWidth=3),
    Line(247,214,280,214,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(247,217,280,217,fill=rgb(0,0,255),lineWidth=3),
    Line(315,246,315,180,fill=rgb(0,0,255),lineWidth=3),
    Line(318,246,318,180,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(355,282,355,235,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(352,282,352,235,fill=rgb(0,0,255),lineWidth=3),
    Line(329,120,329,150,fill=rgb(0,0,255),lineWidth=3),
    Line(332,120,332,150,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(352,205,352,180,fill=rgb(0,0,255),lineWidth=3),
    Line(355,205,355,180,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(352,180,392,180,fill=rgb(0,0,255),lineWidth=3,opacity=40),
    Line(355,180,395,180,fill=rgb(0,0,255),lineWidth=3),
    
    )
# create H's direction    
app.direction = None

# create the rows of score
scores = Group()
def sdscores():

    for i in range(15):
        centerY = 119 + 19 * i
        score = Circle(68,centerY,3,fill='gold')
        scores.add(score)

    for i in range(2):
        centerX = 33 + 18 * i
        score = Circle(centerX,119,3,fill='gold')
        scores.add(score)

    for i in range(5):
        centerY = 38 + 16 * i
        score = Circle(33,centerY,3,fill='gold')
        scores.add(score)



    for i in range(3):
        centerX = 48 + 16 * i
        score = Circle(centerX,38,3,fill='gold')
        scores.add(score)
    
    for i in range(3):
        centerY = 52 + 13 * i
        score = Circle(80,centerY,3,fill='gold')
        scores.add(score)        
        
    for i in range(9):
        centerX = 94 + 13 * i
        score = Circle(centerX,78,3,fill='gold')
        scores.add(score)       
        
    for i in range(3):
        centerY = 33 + 15 * i
        score = Circle(159,centerY,3,fill='gold')
        scores.add(score) 

    for i in range(6):
        centerY = 93 + 15 * i
        score = Circle(159,centerY,3,fill='gold')
        scores.add(score)        

    for i in range(6):
        centerY = 93 + 15 * i
        score = Circle(198,centerY,3,fill='gold')
        scores.add(score)

    for i in range(4):
        centerX = 100 + 13 * i
        score = Circle(centerX,114,3,fill='gold')
        scores.add(score)

    for i in range(4):
        centerX = 100 + 13 * i
        score = Circle(centerX,132,3,fill='gold')
        scores.add(score)
        
    for i in range(18):
        centerX = 49 + 13 * i
        score = Circle(centerX,205,3,fill='gold')
        scores.add(score)

    for i in range(3):
        centerY = 33 + 15 * i
        score = Group(
            Circle(120,centerY,3,fill='gold'),
        
            )
        scores.add(score) 

    for i in range(3):
        centerY = 33 + 15 * i
        score = Group(
            Circle(133,centerY,3,fill='gold'),
            
            )
        scores.add(score) 
      
    for i in range(3):
        centerY = 33 + 15 * i
        score = Group(
            Circle(107,centerY,3,fill='gold'),
            )
        scores.add(score)

    for i in range(3):
        centerY = 150 + 15 * i
        score = Group(
            Circle(133,centerY,3,fill='gold'),
            )
        scores.add(score) 

    for i in range(3):
        centerY = 150 + 15 * i
        score = Group(
            Circle(120,centerY,3,fill='gold'),
            )
        scores.add(score)

    for i in range(3):
        centerY = 150 + 15 * i
        score = Group(
            Circle(107,centerY,3,fill='gold'),
            )
        scores.add(score) 

    for i in range(6):
        centerY = 230 + 14 * i
        score = Group(
            Circle(126,centerY,3,fill='gold'),
            )
        scores.add(score) 

    for i in range(6):
        centerY = 230 + 14 * i
        score = Group(
            Circle(113,centerY,3,fill='gold'),
            )
        scores.add(score) 

    for i in range(6):
        centerY = 230 + 14 * i
        score = Group(
            Circle(100,centerY,3,fill='gold'),
            )
        scores.add(score) 

    for i in range(6):
        centerY = 230 + 14 * i
        score = Group(
            Circle(140,centerY,3,fill='gold'),
            )
        scores.add(score)
        
    for i in range(6):
        centerY = 230 + 14 * i
        score = Group(
            Circle(153,centerY,3,fill='gold'),
            )
        scores.add(score) 
        
    for i in range(6):
        centerY = 230 + 14 * i
        score = Group(
            Circle(166,centerY,3,fill='gold'),
            )
        scores.add(score) 

    for i in range(9):
        centerY = 230 + 14 * i
        score = Group(
            Circle(179,centerY,3,fill='gold'),
            )
        scores.add(score)

    for i in range(9):
        centerY = 230 + 14 * i
        score = Group(
            Circle(189,centerY,3,fill='gold'),
            )
        scores.add(score)

    for i in range(9):
        centerY = 230 + 14 * i
        score = Group(
            Circle(199,centerY,3,fill='gold'),
            )
        scores.add(score)
      
    for i in range(3):
        centerY = 271 + 14 * i
        score = Group(
            Circle(41,centerY,3,fill='gold'),
            )
        scores.add(score) 
        
    for i in range(3):
        centerY = 271 + 14 * i
        score = Group(
            Circle(29,centerY,3,fill='gold'),
            )
        scores.add(score)  

    for i in range(3):
        centerY = 271 + 14 * i
        score = Group(
            Circle(17,centerY,3,fill='gold'),
            )
        scores.add(score)  
        
    for i in range(3):
        centerY = 320 + 14 * i
        score = Group(
            Circle(29,centerY,3,fill='gold'),
            )
        scores.add(score)
        
    for i in range(3):
        centerY = 320 + 14 * i
        score = Group(
            Circle(17,centerY,3,fill='gold'),
            )
        scores.add(score) 
        
    for i in range(3):
        centerY = 320 + 14 * i
        score = Group(
            Circle(41,centerY,3,fill='gold'),
            )
        scores.add(score) 
        
    for i in range(3):
        centerY = 320 + 14 * i
        score = Group(
            Circle(17,centerY,3,fill='gold'),
            )
        scores.add(score)
        
    for i in range(3):
        centerY = 320 + 14 * i
        score = Group(
            Circle(29,centerY,3,fill='gold'),
            )
        scores.add(score)

    for i in range(3):
        centerY = 320 + 14 * i
        score = Group(
            Circle(41,centerY,3,fill='gold'),
            )
        scores.add(score)

    for i in range(3):
        centerY = 364 + 12 * i
        score = Group(
            Circle(17,centerY,3,fill='gold'),
            )
        scores.add(score) 
        
    for i in range(3):
        centerY = 364 + 12 * i
        score = Group(
            Circle(29,centerY,3,fill='gold'),
            )
        scores.add(score) 
       
    for i in range(3):
        centerY = 364 + 12 * i
        score = Group(
            Circle(41,centerY,3,fill='gold'),
            )
        scores.add(score) 

    for i in range(4):
        centerY = 318 + 10 * i
        score = Group(
            Circle(100,centerY,3,fill='gold'),
            )
        scores.add(score) 
        
    for i in range(4):
        centerY = 318 + 10 * i
        score = Group(
            Circle(113,centerY,3,fill='gold'),
            )
        scores.add(score) 
      
    for i in range(4):
        centerY = 318 + 10 * i
        score = Group(
            Circle(126,centerY,3,fill='gold'),
            )
        scores.add(score) 

    for i in range(4):
        centerY = 318 + 10 * i
        score = Group(
            Circle(140,centerY,3,fill='gold'),
            )
        scores.add(score) 


    for i in range(4):
        centerY = 318 + 10 * i
        score = Group(
            Circle(152,centerY,3,fill='gold'),
            )
        scores.add(score) 
       

    for i in range(4):
        centerY = 318 + 10 * i
        score = Group(
            Circle(163,centerY,3,fill='gold'),
            )
        scores.add(score) 

    for i in range(3):
        centerY = 364 + 12 * i
        score = Group(
            Circle(100,centerY,3,fill='gold'),
            )

        scores.add(score)

    for i in range(3):
        centerY = 364 + 12 * i
        score = Group(
            Circle(113,centerY,3,fill='gold'),
            )

        scores.add(score)

    for i in range(3):
        centerY = 364 + 12 * i
        score = Group(
            Circle(126,centerY,3,fill='gold'),
            )

        scores.add(score)

    for i in range(3):
        centerY = 364 + 12 * i
        score = Group(
            Circle(140,centerY,3,fill='gold'),
            )

        scores.add(score)

    for i in range(3):
        centerY = 364 + 12 * i
        score = Group(
            Circle(152,centerY,3,fill='gold'),
            )

        scores.add(score)

    for i in range(3):
        centerY = 364 + 12 * i
        score = Group(
            Circle(163,centerY,3,fill='gold'),
            )

        scores.add(score)

    for i in range(3):
        centerY = 364 + 12 * i
        score = Group(
            Circle(172,centerY,3,fill='gold'),
            )

        scores.add(score)

    for i in range(3):
        centerY = 364 + 12 * i
        score = Group(
            Circle(181,centerY,3,fill='gold'),
            )

        scores.add(score)

    for i in range(3):
        centerY = 364 + 12 * i
        score = Group(
            Circle(190,centerY,3,fill='gold'),
            )

        scores.add(score)

    for i in range(3):
        centerY = 364 + 12 * i
        score = Circle(199,centerY,3,fill='gold')

        scores.add(score)
        
    for i in range(10):
        centerX = 185 + 13 * i
        score = Circle(centerX,39,3,fill='gold')
        scores.add(score)        
        
    for i in range(4):
        centerY = 55 + 12 * i
        score = Group(
            Circle(264,centerY,3,fill='gold'),
            )
        scores.add(score)         

    for i in range(9):
        centerX = 223 + 12 * i
        score = Circle(centerX,105,3,fill='gold')
        scores.add(score)

    for i in range(2):
        centerY = 230 + 12 * i
        score = Circle(228,centerY,3,fill='gold')
        scores.add(score)

    for i in range(2):
        centerY = 230 + 12 * i
        score = Group(
            Circle(238,centerY,3,fill='gold'),
            )
        scores.add(score)

    for i in range(2):
        centerY = 230 + 12 * i
        score = Circle(248,centerY,3,fill='gold')

        scores.add(score)

    for i in range(2):
        centerY = 230 + 12 * i
        score = Circle(258,centerY,3,fill='gold')
        
        scores.add(score)

    for i in range(2):
        centerY = 230 + 12 * i
        score = Circle(268,centerY,3,fill='gold')

        scores.add(score)

    for i in range(7):
        centerY = 115 + 12 * i
        score = Group(
            Circle(230,centerY,3,fill='gold'),

            )
        scores.add(score) 

    for i in range(4):
        centerY = 64 + 10 * i
        score = Group(
            Circle(230,centerY,3,fill='gold'),

            )
        scores.add(score)

    for i in range(7):
        centerX = 313 + 12 * i
        score = Circle(centerX,39,3,fill='gold')
        scores.add(score)

    for i in range(9):
        centerY = 57 + 15 * i
        score = Group(
            Circle(346,centerY,3,fill='gold'),

            )
        scores.add(score)        

    for i in range(6):
        centerY = 92 + 15 * i
        score = Group(
            Circle(362,centerY,3,fill='gold'),

            )
        scores.add(score)    

    for i in range(12):
        centerY = 177 + 16 * i
        score = Group(
            Circle(331,centerY,3,fill='gold'),

            )
        scores.add(score) 
        
    for i in range(9):
        centerY = 66 + 13 * i
        score = Group(
            Circle(377,centerY,3,fill='gold'),

            )
        scores.add(score) 

    for i in range(8):
        centerY = 261 + 13 * i
        score = Group(
            Circle(217,centerY,3,fill='gold'),
            )
        scores.add(score)

    for i in range(8):
        centerY = 261 + 13 * i
        score = Group(
        Circle(233,centerY,3,fill='gold'),
        )
        scores.add(score)

    for i in range(3):
        centerY = 328 + 13 * i
        score = Group(
            Circle(252,centerY,3,fill='gold'),
            )
        scores.add(score)

    for i in range(3):
        centerY = 328 + 13 * i
        score = Circle(263,centerY,3,fill='gold')
            
        scores.add(score)

    for i in range(3):
        centerY = 290 + 13 * i
        score = Group(
            Circle(284,centerY,3,fill='gold'),
            )
        scores.add(score)

    for i in range(3):
        centerY = 290 + 13 * i
        score = Group(
            Circle(296,centerY,3,fill='gold'),
            )
        scores.add(score)

    for i in range(8):
        centerY = 190 + 12 * i
        score = Group(
            Circle(366,centerY,3,fill='gold'),
            )
        scores.add(score)

    for i in range(8):
        centerY = 190 + 12 * i
        score = Group(
            Circle(381,centerY,3,fill='gold'),
            )
            
        scores.add(score)

    for i in range(9):
        centerY = 292 + 12 * i
        score = Group(
            Circle(381,centerY,3,fill='gold'),
            )
        scores.add(score)
        


    for i in range(9):
        centerY = 292 + 12 * i
        score = Group(
            Circle(366,centerY,3,fill='gold'),
            )
        scores.add(score)         


    for i in range(9):
        centerX = 245 + 12 * i
        score = Group(
            Circle(centerX,373,3,fill='gold'),
            )
        scores.add(score)

    for i in range(9):
        centerX = 245 + 12 * i
        score = Group(
            Circle(centerX,386,3,fill='gold'),
            )
        scores.add(score)

    for i in range(3):
        centerX = 295 + 12 * i
        score = Group(
            Circle(centerX,76,3,fill='gold'),
            )
        scores.add(score)

    for i in range(3):
        centerX = 295 + 12 * i
        score = Circle(centerX,66,3,fill='gold')
            
        scores.add(score) 
 
    for i in range(5):
        centerX = 265 + 12 * i
        score = Group(
            Circle(centerX,133,3,fill='gold'),
            )
        scores.add(score) 

    for i in range(5):
        centerX = 265 + 12 * i
        score = Group(
            Circle(centerX,143,3,fill='gold'),
            )
        scores.add(score) 

    for i in range(5):
        centerX = 265 + 12 * i
        score = Circle(centerX,153,3,fill='gold')
            
        scores.add(score) 

    for i in range(5):
        centerX = 265 + 12 * i
        score = Circle(centerX,163,3,fill='gold')
            
        scores.add(score) 

    for i in range(5):
        centerX = 265 + 12 * i
        score = Group(
        
        Circle(centerX,173,3,fill='gold'),
        )
        scores.add(score) 

    for i in range(5):
        centerY = 187 + 12 * i
        score = Circle(289,centerY,3,fill='gold')
        scores.add(score) 
        
    for i in range(5):
        centerY = 187 + 12 * i
        score = Circle(304,centerY,3,fill='gold')
            
        scores.add(score) 


    for i in range(3):
        centerY = 290 + 12 * i
        score = Group(
            Circle(250,centerY,3,fill='gold'),
            )
        scores.add(score)
        


    for i in range(3):
        centerY = 290 + 12 * i
        score = Circle(260,centerY,3,fill='gold')
            
        scores.add(score)
        
#create rows of score when you already won the game
def addscoresline():      
    sdscores()
    
# put all the ghosts on those scores and show the scores
g1.toFront()
g2.toFront()
g3.toFront()
g4.toFront()
g5.toFront()
g6.toFront()
g7.toFront()
addscoresline()

# when you lost the game it will appears and tells you try again, if you don't press
# Run ,you can't move
def GameOver():
    Label('You Died',200,200,size=60,fill='red',bold = True)
    Rect(65,290,272,20,fill='white')
    Label('Press Run to run the program again !',200,300,size=15,fill='red',bold = True)
    
    app.stop()
    
#create the sign of the win game,when you won the game, it will reminds you    
gamewin = Group(
    Rect(60,200,280,60,fill = 'white'),
    Label('You Win',200,100,size=60,fill='gold',bold = True),
    )
endgame = Group(
    Rect(220,216,110,20),
    Label('I HATE IT BYEBYE',274,225,fill='red',size=10,bold = True),
    Line(280,240,280,255,arrowStart=True),
    )
nextgame = Group(
    Rect(83,216,110,20),
    Label('SEE YOU NEXT GAME',138,227,fill='red',size=10,bold = True),
    Line(140,240,140,255,arrowStart=True),
    )
gamewin.add(nextgame)
gamewin.add(endgame)
gamewin.visible = False

#move the H and if you hit the wall or ghost you will lost the game, if you touch the score, it will remove score from scores then you will get the mark and if you
#get 200 points you will win the game and all the rows of score which you eat will appear again. 
def onKeyHold(keys):
    if 'up' in keys:
        H.centerY -= 4
        H_left.centerY -= 4
        H.visible = True
        H_left.visible = False
        app.direction = 'up'
        H.rotateAngle = -90
        
    elif 'down' in keys:
        H.centerY += 4
        H_left.centerY += 4
        H.visible = True
        H_left.visible = False
        app.direction = 'down'
        H.rotateAngle = 90
        
    elif 'left' in keys:
        H.centerX -= 4
        H_left.centerX -= 4
        H.visible = False
        H_left.visible = True
        app.direction = 'left'
            
    elif 'right' in keys:
        H.centerX += 4
        H_left.centerX += 4
        H.visible = True
        H_left.visible = False
        H.rotateAngle = 0
        app.direction = 'right'
    for score in scores.children:
        
        if H.hitsShape(score):
            scores.remove(score)
            mark.value += 1
    if H.hitsShape(g1):
        GameOver()
    if H.hitsShape(w):
        GameOver()
    if H.hitsShape(g2):
        GameOver()
    if H.hitsShape(g2):
        GameOver()
    if H.hitsShape(g3):
        GameOver()
    if H.hitsShape(g4):
        GameOver()
    if H.hitsShape(g5):
        GameOver()
    if H.hitsShape(g6):
        GameOver()
    if H.hitsShape(g7):
        GameOver()
    if 'q' in keys:
        mark.value = 200
        scores.clear()
    if mark.value >= 200:
        gamewin.visible = True
        app.stop()
        addscoresline()
        
# let all those ghosts to move and turn around but it will have range and domain, prevents they move to other place or out the canvas         
def onStep():
    g2.centerY += g2.dy
    if g2.bottom > 390:
        g2.dy = 0 
        g2.centerX += g2.dx
        if g2.left < 10:
            g2.dx = -g2.dx
        if g2.right > 81:
            g2.dx = 0
            g2.centerX = 71
            g2.centerY = 373
            g2.dy = -4
    if g2.top < 103:
        g2.dx = -4
        g2.dy = 4

    g3.centerY += g3.dy
    if g3.bottom > 353:
        g3.dy = 0 
        g3.centerX += g3.dx
        if g3.left < 243:
            g3.dx = -g3.dx
        if g3.right > 340:
            g3.dx = 0
            g3.centerX = 331
            g3.centerY = 337
            g3.dy = -4
    if g3.top < 150:
        g3.dx = -4
        g3.dy = 4
    
        
    g6.centerY += g6.dy
    if g6.bottom > 217:
        g6.dy = 0 
        g6.centerX += g6.dx
        if g6.left < 93:
            g6.dx = -g3.dx
        if g6.right > 244:
            g6.dx = 0
            g6.centerX = 230
            g6.centerY = 195
            g6.dy = -4
    if g6.top < 60:
        g6.dx = -4
        g6.dy = 4
    
        
    g7.centerX += g7.dx
    if g7.right > 200:
        g7.dx = 0
        g7.centerY += g7.dy
        if g7.bottom > 180:
            g7.dy = -g7.dy
        if g7.top < 60:
                g7.dy = 0
                g7.centerY = 80
                g7.dx = -2
    if g7.left < 58:
        
        g7.dx = 2
        g7.dy = 2
                    
    g1.centerX += g1.dx
    if g1.right > 390:
        g1.dx = 0 
        
        g1.centerY += g1.dy
        if g1.top < 180:
            g1.dy = 3
        if g1.bottom > 395 :
                g1.dy = 0
                g1.centerY = 374
                g1.dx = -3
    if g1.left < 93:
        
        g1.dx = 3
        g1.dy = -3
        
    g5.centerX += g5.dx
    if g5.right > 200:
        
        g5.dx = 0
        
        g5.centerY += g5.dy
        if g5.bottom > 355:
            g5.dy = -g5.dy
        if g5.top < 240:
                g5.dy = 0
                g5.centerY = 255
                g5.dx = -1
    if g5.left < 50:
        
        g5.dx = 1
        g5.dy = 1
        
    g4.centerY += g4.dy
    if g4.bottom > 176:
        g4.dy = 0 
        g4.centerX += g4.dx
        if g4.left < 250:
            g4.dx = -g4.dx
        if g4.right > 392:
            g4.dx = 0
            g4.centerX = 375
            g4.centerY = 157
            g4.dy = -3
    if g4.top < 57:
        g4.dx = -3
        g4.dy = 3           
