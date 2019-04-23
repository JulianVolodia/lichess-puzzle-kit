# Lichess puzzle developer starter kit

In order to hack the lichess puzzle UI, you need to get some puzzles and their associated games in your local database. Here's how.

```
mongorestore -d lichess -c puzzle puzzle.bson
mongorestore -d lichess -c game5 game.bson
```

This sets you up with 193 puzzles and their associated games.

The puzzles start at ID=61053, which is where a new user gets started.

Here's a complete list of the puzzle IDs in this DB export:

```
61053 61054 61055 61056 61057 61058 61059 61060 61061 61062 61063 61064 61065 61066 61067 61068 61069 61070 61071 61072 61073 61074 61075 61076 61077 61078 61079 61080 61081 61082 61083 61084 61085 61086 61087 61088 61089 61090 61091 61092 61093 61094 61095 61096 61097 61098 61099 61100 61101 61102 61103 61104 61105 61106 61107 61108 61109 61110 61111 61112 61113 61114 61115 61116 61117 61118 61119 61120 61121 61122 61123 61124 61125 61126 61127 61128 61129 61130 61131 61132 61133 61134 61135 61136 61137 61138 61139 61140 61141 61142 61143 61144 61145 61146 61147 61148 61149 61150 61151 61152 61153 61154 61155 61156 61157 61158 61159 61160 61161 61162 61163 61164 61165 61166 61167 61168 61169 61170 61171 61172 61173 61174 61175 61176 61177 61178 61179 61180 61181 61182 61183 61184 61185 61186 61187 61188 61189 61190 61191 61192 61193 61194 61195 61196 61197 61198 61199 61200 61201 61202 61203 61204 61205 61206 61207 61208 61209 61210 61211 61212 61213 61214 61215 61216 61217 61218 61219 61220 61221 61222 61223 61224 61225 61226 61227 61228 61229 61230 61231 61232 61233 61234 61235 61236 61237 61238 61239 61240 61241 61242 61243 61244 61245 61246 61247 61248 61249 61250 61251 61252 125272
```

Happy coding.
