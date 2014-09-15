decl
	integer a,i,n,count,prime(integer a);
enddecl
	
integer prime(integer a)
{
	integer flag;
	flag =0;
	i=2;
	if(a==1) then
		print(a);
	endif;

	while(i<=a/2) do
		if(a%i==0) then
			flag = 1;
			break;
		else
			i = i+1;
		endif;
	endwhile;	

	if(flag == 0) then 
		print(a);
	endif;

return 0;	
}
 
			
integer main(){
	breakpoint;
	read(n);
	integer val;
	count = 1;
	while(count<=n) do 
		val = prime(count);
		count = count + 1;
	endwhile;
	return 0;

}

