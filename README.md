# 2-
module logic_gate (a, b, x, y, z, n, m);

    input a, b;

    output x, y, z, n, m;

    wire x, y, z, n, m;

    // and gate
    assign x = a & b;

    // or gate
    assign y = a | b;

    // xor gate
    assign z = a ^ b;

    // nor gate
    assign n = ~(a | b);

    // nand gate
    assign m = ~(a & b);

endmodule
