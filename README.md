$(document).ready(function() {
    // process bar
    setTimeout(function() {
        firstQuestion();
        $('.spinner').fadeOut();
        $('#preloader').delay(350).fadeOut('slow');
        $('body').delay(350).css({
            'overflow': 'visible'
        });
    }, 600);
})
const textConfig = {
  text1: "Hờ lô bấy bề",
  text2: "Tui có điều này muốn nói dới bạn á!!!",
  text3: "Tui là Santa của bạn nèeeeeee",
  text4: "Hế lô anh/ chị/ bà/ ông/ em, dị là một mùa Giáng sinh nữa sắp đến và chớp mắt thì cũng đã hong xa trường, xa lớp, xa IREC nửa năm òi á. Nhưng mà hăm sao, vì mọi người đếu đang ở đây, cùng họp, cùng xem phim, cùng thức khuya, cùng cười hahaha nên là mọi chuyện vẫn ổn đúng hăm. Vì năm nay hong gặp nhau được nên món quà này sẽ thay mặt tui chúc mấy người ha. Đầu tiên là, cảm ơn anh/ chị/ ông/ bà/ em đã chọn IREC để bây giờ mới có dịp như này. Cái nữa á, là đừng để thời tiết đánh lừa rằng bạn cần ngừi eoo, bạn chỉ cần 1 nồi lẩu bập bùng khói lửa hoi. Hơn thế nữa, dù bạn là ai, tui vẫn mong bạn sẽ thật vui vẻ, hạnh phúc, xinh đẹp, giỏi giang như bạn của hiện tại, hơn thế nữa càng tốt hihi. Dù mọi người ở đâu, IREC vẫn luôn là nơi cho bạntrở về được á. Dị nên bạn dù có đang mệt mỏi, căng thẳng, ngập ngụa trong deadline thì tui biết là bạn vẫn đang cố hết sức mình. Bạn xuất sắc lắm *xoa đầu xoa đầu*. Một lời chúc cuối cùng quan trọng không kém là mong bạn tích góp đủ đầy để sẵm sửa đồ tết thiệt hịn nhaa. Merry Christmas <3 ",
  text5: "Ôi mình hạnh phúc quá",
  text6: "Ôi mình quá hạnh phúc",
  text7: "Đọc xong thư bạn thấy dui hemmmm",
  text8: "Gửi cho tớ <3",
  text9: "Vì cậu đẹp try vlllll",
