import math

def bloom_sphere(samples, radius, zspacing):
# John Edmark
# http://www.instructables.com/id/Blooming-Zoetrope-Sculptures/?ALLSTEPS
# elfnor's orginal code
# https://github.com/elfnor/bloom_sphere


    golden_angle = 2.39996322972865332 # radians ~137.5 degrees
    points = []
    edges = []
    faces = []
    n = samples/2
    # for low values of zspacing e1, e2 = 13, 21 looks better
    if abs(zspacing) > 0.005:
        e1, e2 = 8, 13
    else:
        e1, e2 = 21, 34
    for i in range(samples):
        zi = i - n
        theta = zi * golden_angle
        zc = zi * zspacing
        phi = math.atan2(radius, zc)
        x = radius*math.sin(phi)*math.cos(theta)
        y = radius*math.sin(phi)*math.sin(theta)
        z = radius*math.cos(phi)
        points.append([x,y,z])

        if (i + e1) < samples - 1:
            edges.append( (i, i + e1) )
        if (i + e2) < samples - 1:
            edges.append( (i, i + e2) )
        if (i + e1 + e2) < samples - 1:
            faces.append([i, i + e1, i + e1 + e2, i + e2] )

    return points, edges, faces

def sv_main(samples=400, radius=2.0, zspacing=0.05):
    verts_out = []
    edges_out = []
    faces_out = []

"""
in samples s d=400 n=2
in radius s d=10.0 n=2
in zspacing s d=0.04 n=2
out verts_out v
out edges_out s
out faces_out s
"""

p, e, f = bloom_sphere(samples, radius, zspacing)

verts_out.extend([p])
edges_out.extend([e])
faces_out.extend([f])
