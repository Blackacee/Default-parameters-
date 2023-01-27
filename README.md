# Default-parameters-

function printMsg(msg='Default value for msg.') {
 console.log(msg);
}
printMsg(); // -> "Default value for msg."
printMsg(undefined); // -> "Default value for msg."
printMsg('Now my msg in different!'); // -> "Now my msg in different!"
