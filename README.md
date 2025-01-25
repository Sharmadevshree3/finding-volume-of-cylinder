# finding-volume-of-cylinder
#include <stdio.h>
int main()
{
    float radius, height, surface_area, volume;
    printf("Enter  value for  radius and height of a cylinder : \n");
    scanf("%f%f", &radius, &height);
    volume = (22 / 7) * radius * radius * height;
    printf(" Volume of cylinder is : %f", volume);
    return 0;
}
