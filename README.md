# main
#DGFN 2 Assgn 1 2023
#ryan Groskopf
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

if __name__ == "__main__":
    test_rectangle_area()
    test_rectangle_volume()
    # Call other test functions
