# literate-waddle
echo wlcm to mitali first repl try

num=6
fact=1
c=$num

while [ $c -gt 1 ];
 do
    fact=$(($fact * $c))
    c=$(($c -1 ))
done
echo $fact
