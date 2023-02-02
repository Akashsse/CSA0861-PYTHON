# CSA0861-PYTHON
def areisIsomorphic(string1,string2):
    m=len(string1)
    n=len(string2)
    if m != n:
        return False
    marked=[False] * max_chars
    map=[-1] * max_chars
    for i in range(n):
        if map[ord(string1[i])]==-1:
            if marked[ord(string2[i])]==True:
                return False
            marked[ord(string2[i])]=True
            map[ord(string1[i])]=string2[i]
        elif map[ord(string1[i])] != string2[i]:
            return False
    return True

areIsomorphic("aab","xxy")
