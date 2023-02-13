## Lab 04

- Name: Isabella Livingston
- Email: livingston.70@wright.edu

## Part 1 Answers

1. `grep -x "714" grepdata.txt `
2. `grep -i "CA" grepdata.txt`
3. `grep "@" grepdata.txt`
4. `grep ", 2" grepdata.txt `

## Part 2 Answers

1. `sed -r 's/<\/[^>]*>//g' sedfile.html`
2. `sed 's/ <li>/- /g' sedfile.html`
3. `sed 's/<h1>/# /g' sedfile.html`
4. `sed 's/<h2>/## /g' sedfile.html`
5. `sed -e 's/<ul>//g' -e 's/<html>//g' sedfile.html`
6. `sed 's/Batches/Matches/g' sedfile.html`

## Part 3 Answers

1. `awk '/Bil/ {print}' records.txt`
2. `awk '/42/ {print $3}' records.txt`
3. `awk '/wright.edu/ {print $1",",$2":", $3}' records.txt`
4. `awk '/1234/&&/wright.edu/ {print $2,"Last favorite number is:",$4}' records.txt`
5. `awk '{print $1,$2,"N0T@PL@!NP@$$W0RD",$4,$5,$6}' <records.txt >updaterecords.txt`
