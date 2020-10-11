Property transition memungkinkan kita untuk dapat mengubah nilai dari property HTML secara halus
Penggunaan:
 transition: [property] <durasi: m/ms> [fungsi/timing function] [delay];
note: [] => Opsional
	  <> => Wajib

Ini beberapa property yang bisa di animasikan:
- background-color
- background-position
- background-size
- border
- color
- filter
- font-size
- line-height
- top left bottom right
- margin padding
- width height
- opacity
- transform
- word-spacing
- letter-spacing

Dan yang tidak bisa dianimasikan:
- font-family
- display
- position

Timing function yang bisa kita pakai:
- ease
- ease-in
- ease-out
- ease-in-out
- linear
- cubic-bezier(w,x,y,z) => Untuk value-nya kita bisa tentukan lewat inspect element pada tab CSS. Nanti disana akan ada logo cubic-bezier