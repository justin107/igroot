# igroot

    const RandomId = len => Math.random().toString(36).substr(3, len);
    const id = RandomId(10);
    id => "jg7zpgiqva"

    const RoundNum = (num, decimal) => Math.round(num * 10 ** decimal) / 10 ** decimal;
    const num = RoundNum(1.69, 1);
