class simpleinterest
{
    int p,t;
    double ans,r;//instance variable
    void init(int P,double R, int T)//interactive input
    {
        p=P;
        r=R;
        t=T;
    }
    void calc()
    {
        ans=p*r*t/100;
    }
    void didsplay()
    {
        System.out.println(ans);
    }
}
