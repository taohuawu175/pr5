# pr5
    public void test11() {

        long start = System.currentTimeMillis();
        int a = 0;
        for(int i=0;i<1000000000;i++){
            a*=2;
            a/=2;
        }
        long useTime = System.currentTimeMillis()-start;
        System.out.println("useTime:"+useTime);
    }
