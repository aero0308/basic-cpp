# basic-cpp

# Will be adding basic programming questions in CPP.

//SEARCHING IN 2 ARRAY / MATRIX

int n,m;
cin>>n>>m;
int arr[n][m];

    for(int i=0;i<n;i++)
    {
         for(int j=0;j<m;j++)
         {
              cin>>arr[i][j];
         }
    }
    int x;cin>>x;

    bool flag=false;
    for(int i=0;i<n;i++)
    {
         for(int j=0;j<m;j++)
         {
              if(arr[i][j]==x)
              {
                   cout<<i<<" "<<j<<endl;
                   flag=true;
              }
         }
    }

    if(flag)
    {
         cout<<"element is found"<<endl;
    }
    else
    {
         cout<<"element not found"<<endl;
    }
