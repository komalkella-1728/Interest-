#include <stdio.h>
#include <math.h>

int main() {
    float p, r, t, si, ci, amount;

    printf("Enter Principal (P): ");
    scanf("%f", &p);

    printf("Enter Rate of Interest (R): ");
    scanf("%f", &r);

    printf("Enter Time (T in years): ");
    scanf("%f", &t);

    // Simple Interest
    si = (p * r * t) / 100;
    printf("\nSimple Interest = %.2f\n", si);

    // Compound Interest
    amount = p * pow((1 + r/100), t);
    ci = amount - p;
    printf("Compound Interest = %.2f\n", ci);

    return 0;
}
