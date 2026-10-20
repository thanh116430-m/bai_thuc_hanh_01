#include <stdio.h>
#include <math.h>

int main() {
    double a, b, c, delta, x1, x2;

    printf("Nhap a, b, c: ");
    scanf("%lf%lf%lf", &a, &b, &c);

    if (a == 0) {
        if (b == 0) {
            if (c == 0) {
                printf("Vo so nghiem");
            } 
			else {
                printf("Vo nghiem");
            }
        } 
		else {
            printf("Phuong trinh bac nhat co nghiem x = %.2f", -c / b);
        }
    } else {
        delta = b * b - 4 * a * c;

        if (delta < 0) {
            printf("Vo nghiem thuc");
        } 
		else if (delta == 0) {
            printf("Nghiem kep x = %.2f", -b / (2 * a));
        } 
		else {
            x1 = (-b + sqrt(delta)) / (2 * a);
            x2 = (-b - sqrt(delta)) / (2 * a);

            printf("x1 = %.2f, x2 = %.2f", x1, x2);
        }
    }
    return 0;
}

