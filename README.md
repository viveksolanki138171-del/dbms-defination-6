# dbms-defination-6
--Write a PL/SQL block to calculate the square and cube of the given number.



set serveroutput on;


declare
v_num number; v_square number; v_cube number;

begin
v_num := &enter_number; v_square := v_num * v_num;
v_cube	:= v_num * v_num * v_num;


dbms_output.put_line('number : ' || v_num); dbms_output.put_line('square : ' || v_square); dbms_output.put_line('cube	: ' || v_cube);

end;
/
