# DGFN 2 Assgn 1 2023
# Ryan Groskopf
#this pytrest the Area and the Volume of the asssinment
from A_V_calc_starter import rectangle_area, rectangle_volume

#this one tests for Area of a rectangle
def test_rectangle_area():
    assert rectangle_area(2, 3) == 6  # Expected result is 6
    assert rectangle_area(4, 5) == 20  # Expected result is 20
    
#this one test for volume of a rectangle
def test_rectangle_volume():
    assert rectangle_volume(2, 3, 4) == 24  # Expected result is 24
    assert rectangle_volume(4, 5, 6) == 120  # Expected result is 120
    
#this is for the Area of Triangle
def test_Triangle_Area():
    assert Triangle_Area(3, 4) == 6.0  # Expected result is 6.0
    assert Triangle_Area(5, 12) == 30.0  # Expected result is 30.0

#this is for the Area of a Circle
def test_circle_area():
    assert round(circle_area(2), 2) == 12.57  # Expected result is 12.57 (rounded)
    assert round(circle_area(3), 2) == 28.27  # Expected result is 28.27 (rounded)

#this is for the Area of a ellipse 
def test_ellipse_area():
    assert round(ellipse_area(10, 10), 2) == 314.16  # Expected result is 314.16 (rounded)
    assert round(ellipse_area(5, 10), 2) == 157.08  # Expected result is 157.08 (rounded)

if __name__ == "__main":
    test_rectangle_area()
    test_rectangle_volume()
    test_Triangle_Area()
    test_circle_area()
    test_ellipse_area()

