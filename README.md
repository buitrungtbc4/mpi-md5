# mpi-md5
## Make file: 
`inline code` mpicc –Wall –o mpi-md5 mpi-md5.c –lcrypto –lssl
## Run file:
`inline code` mpirun –np <số tiến trình> -host <[tên host,]> ./ mpi-md5 (đường dẫn tới file vừa make) <mã md5 32 kí tự> <số kí tự tối đa của mật khẩu>.
