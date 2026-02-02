# Python-program-to-check-whether-the-given-integer-is-a-prime-number-or-not
num = int(input("Enter an integer: "))
isprime = 1 #assuming that num is prime
for i in range(2,num//2):
    if (num%i==0):
        isprime = 0
        break
if(isprime==1):
    print(num, "is a prime number")
else:
    print(num, "is not a prime number")
output:
Enter an integer: 1101
103
105
107
109
110
112
114
116
118
121
123
125
127
129
130
132
134
136
138
141
143
145
147
149
150
152
154
156
158
161
163
165
167
169
170
172
174
176
178
181
183
185
187
189
190
192
194
196
198
