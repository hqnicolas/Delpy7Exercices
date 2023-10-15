# Programa em delphy para Traduzir Cores de Resistores


1% Marrom
2% vermelho
3% laranja
5%  gold
10% prata


___________________________________________________________________________________________________


case zero of
0: shape1.brush.color:=clBlack
1: shape1.brush.color:=clmarrom
2: shape1.brush.color:=clred
end;



begin
zero:=0;
  tam:=length(Edit1.text);
  numero:=Edit1.text;
  cont:=tan;
  repeat
  if numero[cont]='0'then zero:=(zero+1)
  else
  cont:=1;
  cont:=(cont-1)
  until cont=2;
   case zero of
   0:Shape1.Brush.Color:=clBlack;
   1:Shape1.Brush.color:=clMaroon;
   2:Shape1.Brush.color:=clRed;
   3:shape1.Brush.Color:=clFuchsia;
   4:Shape1.Brush.Color:=clYellow;
   5:Shape1.Brush.Color:=clGreen;
   6:Shape1.Brush.Color:=clBlue;
   7:Shape1.Brush.Color:=clPurple;
   8:Shape1.Brush.Color:=clGray;
   9:Shape1.Brush.Color:=clWhite;
   10:Shape1.Brush.Color:=clOlive;
   11:Shape1.Brush.Color:=clSilver;
end;

 case Edit1.Text[2] of
   '0':Shape2.Brush.Color:=clBlack;
   '1':Shape2.Brush.color:=clMaroon;
   '2':Shape2.Brush.color:=clRed;
   '3':shape2.Brush.Color:=clFuchsia;
   '4':Shape2.Brush.Color:=clYellow;
   '5':Shape2.Brush.Color:=clGreen;
   '6':Shape2.Brush.Color:=clBlue;
   '7':Shape2.Brush.Color:=clPurple;
   '8':Shape2.Brush.Color:=clGray;
   '9':Shape2.Brush.Color:=clWhite;
  end;
    case Edit1.Text[1] of
   '0':Shape3.Brush.Color:=clBlack;
   '1':Shape3.Brush.color:=clMaroon;
   '2':Shape3.Brush.color:=clRed;
   '3':shape3.Brush.Color:=clFuchsia;
   '4':Shape3.Brush.Color:=clYellow;
   '5':Shape3.Brush.Color:=clGreen;
   '6':Shape3.Brush.Color:=clBlue;
   '7':Shape3.Brush.Color:=clPurple;
   '8':Shape3.Brush.Color:=clGray;
   '9':Shape3.Brush.Color:=clWhite;
  end;
