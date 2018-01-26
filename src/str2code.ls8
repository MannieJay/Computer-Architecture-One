/**
 * Simple program that converts a string into binary bytes for use in source
 * code for the simulated computer
 */

const argv = process.argv.slice(2);

if (argv.length === 0) {
    console.error('usage: str2code string');
}

const str = argv.join(' ');

/**
 * Convert a value into a binary string of at least 8 bits
 */
function makeBinString(val) {
    let str = val.toString(2);
 
    while (str.length < 8) {
        str = '0' + str;
    }

    return str;
}

// Print out the values in the string
for (let i = 0; i < str.length; i++) {
    const val = str.charCodeAt(i);
    const binVal = makeBinString(val);

    let ascii

    if (val == 10) {
        ascii = '[newline]';
    } else if (val == 13) {
        ascii = '[carriage return]';
    } else if (val == 32) {
        ascii = '[space]';
    } else if (val < 32 || val > 126) {
        ascii = '[??]';
    } else {
        ascii = str[i];
    }
    
    console.log(`${binVal} # ${ascii}`);
}