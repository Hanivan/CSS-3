Penulisan fungsi keyframes:
 @keyframes [name] {
 	from {
 		[property CSS]
 	} to {
 		[property CSS]
 	}
 }
	ATAU
 @keyframes [name] {
 	0% {
 		[property CSS]
 	}

 	100% {
 		[property CSS]
 	}
 }

Penggunaan fungsi keyframes pada property css:
 animation: [name(harus sesuai dengan variabel yang dibuat)];

Value yang bisa dipakai di property animation:
 - [name] => wajib ada
 - [duration] => durasi dari animasinya, sama persis dengan transition
 - [timing-function] => sama persis dengan transition
 - [delay] => sama persis dengan transition
 - [iteration-count] => perulangan, bisa ditentukan/terus-menerus(infinite)
 - [direction]
 	* normal
 	* reverse
 	* alternate
 	* alternate-reverse
 - [fill-mode]
 	* none
 	* forwards
 	* backwards
 	* both
 - [play-state]
 	* running (default)
 	* paused (bisa dikombine dengan JS)