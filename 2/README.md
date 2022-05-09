# snippy

function notNull(val) { return val !== null; }

(await contract.contributions.call(player)).words.filter(notNull).reduce((a, b) => a + b, 0)
