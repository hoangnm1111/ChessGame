# BÁO CÁO GITHUB.
<a name = "I"></a>
# Cấu trúc project
<a name="markdown"></a>
Project gồm 4 file chính:
- Menu.py, button.py: menu trò chơi
- ChessMain.py: Tệp điều khiển chính. Xử lý đầu vào từ người dùng.Hiển thị trạng thái bàn cờ qua từng nước đi.
- ChessEngine.py: Lưu trữ tất cả thông tin về trạng thái hiện tại của trò chơi cờ vua.Xác định những nước đi hợp lệ tại trạng thái hiện tại. Lưu giữ bản ghi về các nước đi đã thực hiện.
- ChessAI.py: AI cờ vua
#  Hướng dẫn chạy code
- Chạy trên pycharm (vì chạy trên visual studio gặp lỗi)
- Import thư viện pygame
- Vào file Menu.py để chạy trò chơi

# Phân công công việc
- Nguyễn Nam Hoàng: Xây dựng menu, hình ảnh bàn cờ(drawBoard, drawPiece), hình ảnh các nút reset, return, quân cờ; xây dựng AI cờ vua 
- Trần Nhật Hoàng: Class CastleRights, xây dựng 1 phần class GameState: gồm các hàm: hàm khởi tạo, makeMove, undoMove, updateCastleRights, squareUnderAttack, inCheck, checkForPinsAndChecks, getCastleMove, getKingsideCastleMoves, getQueensideCastleMoves (trong file ChessEngine.py)
- Giáp Việt Hùng:Xây dựng 1 phần class GameState: gồm các hàm: getPawnMove,getRookMove, getKnightMove, getBishopMove, getQueenMove, getKingMove, getAllPossibleMoves, getValidMoves (trong file ChessEngine.py), xây dựng các hàm: highlightSquares(file chessMain.py)
- Nguyễn Văn Hưng: Xây dựng class Move(trong file ChessEngine.py); các hàm animatedMove, drawMoveLog, drawEndGameText(file chessMain.py);
vòng lặp while trong hàm main ( từ while running: -> hết hàm main)
