//Beta

Functions implemented successfully:
1.  void mdi_init(mdi_ptr_ptr x);
2.  mdi_ptr read_mdi(mdi_ptr x); 				
3.  int print_mdi(mdi_ptr x); 
4.  void mdi_set(mdi_ptr_ptr dst, mdi_ptr src);
5.  void mdi_set_int(mdi_ptr_ptr dst, long int src); 
6.  void mdi_add(mdi_ptr_ptr dst, mdi_ptr src1, mdi_ptr src2); 
7.  void mdi_mul(mdi_ptr_ptr dst, mdi_ptr src1, mdi_ptr src2);
8.  void mdi_div(mdi_ptr_ptr dst1, mdi_ptr_ptr dst2, mdi_ptr src1, mdi_ptr src2);
9.  void mdi_quo(mdi_ptr dst, mdi_ptr src1, mdi_ptr src2);
10. void mdi_rem(mdi_ptr_ptr dst, mdi_ptr src1, mdi_ptr src2);
11. int mdi_cmp_zero(mdi_ptr arg1);


The program, on execution, computes (i) addition of n multi-precision integer inputs, (ii) 1000! and, (iii) 2^10000. 
