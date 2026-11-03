addCoins = function(amount) {
        return typeof log != 'undefined' && log !== null ? log.log({
            event: "adjustCoins",
            value: amount
        }) : void 8;
    };
addCoins(42)
