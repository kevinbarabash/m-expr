# Planning

How to represent equations and expressions?

    var expr1 = ['2', '*', ['3', '-', '4']];
    var expr2 = [['2', '/', '3'], '+', ['5', '/', '6']];
    var eq1 = [['2', '*', 'x', '+', '1'], '=', ['7']];
    var expr3 = [['1', '/', '2'], '/', ['3', '/', '4']];
    var expr4 = ['2', '*', 'x', '/', '3', '/', 'y']; // (2x)/(3y)
    var expr4a = [['2', '*', 'x'], '/', ['3', '*', 'y']];
 
How to show (1/2) / (3/4) ? expr4a