1> Thêm submodule
  git submodule add https://github.com/DatMV01/cqrs-eventsourcing-springboot-axon.git

2> Rồi commit:
  git add .
  git commit -m "Add axon submodule"

4> Sau này update submodule:
  cd cqrs-eventsourcing-springboot-axon
  git pull origin main

5> quay lại repo cha:
  cd ..
  git add cqrs-eventsourcing-springboot-axon
  git commit -m "Update submodule"

6> Kiểm tra submodule:
  git submodule status
