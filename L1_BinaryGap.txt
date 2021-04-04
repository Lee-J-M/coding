def solution(N):
    bin = str(format(N, 'b'))
    bin = bin.strip('0')
    bin = bin.split('1')
    return len(max(bin))