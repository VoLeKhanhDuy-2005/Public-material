# Một số lệnh cơ bản
## Khôi phục dữ liệu local về remote
git restore --source=origin/main -- \src/main/java/com/uteshop/dao/impl/web/AttributesDaoImpl.java \src/main/webapp/commons/web/footer.jsp
# Clone file / thư mục từ nhánh
git clone --branch <tên-nhánh> <địa chỉ url-repo>
# Chỉ clone 1 thư mục
git clone --no-checkout https://github.com/VoLeKhanhDuy-2005/VoLeKhanhDuy_23110196_LTWEB_BT123.git

cd VoLeKhanhDuy_23110196_LTWEB_BT123

git sparse-checkout init --cone

git sparse-checkout set BaiTap2

git checkout
