# mpi-md5
## Make file: 
`mpicc –Wall –o mpi-md5 mpi-md5.c –lcrypto –lssl`
## Run file:
`inline code mpirun –np <số tiến trình> -host <[tên host,]> ./mpi-md5 <mã md5 32 kí tự> <số kí tự tối đa của mật khẩu>`.
