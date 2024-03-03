# thuh-phung
#include<stdio.h>
#include<conio.h>
void
main ()
{
  int a, b;
  char dv, chuc, tram;
  clrscr ();
  printf ("\nMo phong phep nhan tay\n\n");
  printf ("%20d\n", a);
  printf ("%15c%5d\n", 'x', b);
  printf ("%20s\n", "-------");
  printf ("%20d\n", a * dv);
  printf ("%19d\n", a * chuc);
  printf ("%18d\n", a * tram);
  printf ("%20s\n", "-------");
  printf ("%20ld\n", long (a) * b);
  getch ();

}
