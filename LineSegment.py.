# LineSegment.py:

# Point class definition
import self


class Point:


 # parameterized constructor
def __init__(self, x, y):


    self._x_coord = x
self._y_coord = y


# function to get x-coordinate
def get_x_coord(self):


    return self._x_coord


# function to get y-coordinate
def get_y_coord(self):


    return self._y_coord


# function to find distance between two points
def distance_to(self, p):


    x = (self._x_coord - p.get_x_coord()) * (self._x_coord - p.get_x_coord())
y: object = (self._y_coord - p.get_y_coord()) * (self._y_coord - p.get_y_coord())
return (x + y) ** 0.5


# class LineSegment definition
class LineSegment:


# parameterized constructor
def __init__(self, ep1, ep2):


    self._endpoint_1: object = ep1
self._endpoint_2 = ep2


# function to find distance between two end points of line segment
def length(self):


    return self._endpoint_1.distance_to(self._endpoint_2)


# function to find slope of line segment
def slope(self1):


    x = self1._endpoint_2.get_x_coord() - self1._endpoint_1.get_x_coord()
y = self._endpoint_2.get_y_coord() - self._endpoint_1.get_y_coord()
return y / x


# function to check whether the two line segments are parallel to each other
def is_parallel_to(self, line_seg_2):
    """

    :type line_seg_2: object
    """


if self.slope() == line_seg_2.slope():
  True
else: False

# creates two points
point_1 = Point(7, 4)
point_2 = Point(-6, 18)

# prints the distance between them
print(point_1.distance_to(point_2))

# creates a line segment with two given points
line_seg_1 = LineSegment(point_1, point_2)

# prints line segments length
print(line_seg_1.length())

# prints line segments slope
print(line_seg_1.slope())

# creates two points
point_3 = Point(-2, 2)
point_4 = Point(24, 12)

# creates a line segment with two given points
line_seg_2 = LineSegment(point_3, point_4)

# prints if line_seg_1 is parallel to line_seg_2 or not
print(line_seg_1.is_parallel_to(line_seg_2))
